# WRDS — a short guide for your replication project

ML & FinTech · 115-1

**WRDS** (Wharton Research Data Services) is the data platform most finance papers use.
It gives one login to many databases: stock prices, financial statements, analyst forecasts,
bonds, options and more. NYCU pays for a subscription, so you can use it for free.

If the paper you are replicating uses US market data, it very likely came from here.

| Database | What it holds | Typical use |
|---|---|---|
| **CRSP** | Daily and monthly prices, returns and volume for US stocks, from 1925 | Returns, portfolios, event studies |
| **Compustat** | Financial statements of listed firms | Accounting ratios, firm characteristics |
| **IBES** | Analyst forecasts | Earnings surprises |
| **OptionMetrics** | Option prices and implied volatility | Volatility, option strategies |

NYCU does not subscribe to everything. Inside WRDS, databases shown in **blue** are available
to you; those in **grey** are not.

---

## 1. Get an account (do this now; approval is not instant)

1. Register at <https://wrds-www.wharton.upenn.edu/register/> with your **NYCU email address**,
   then click the link in the confirmation email.
2. Fill in the NYCU Library's WRDS application form: <https://forms.gle/hnP94tJ4fFSZC5o39>
3. Wait for the approval email and follow its instructions.

If the form has moved or your approval does not arrive, ask the **NYCU Library**.

R2 (data) is due **10/19**. Apply this week, not the week before.

---

## 2. Download data from the website

Example: daily stock data from CRSP.

1. Log in at <https://wrds-www.wharton.upenn.edu/login/>.
2. Click **Get Data**. Choose a database from the list, or use the concept groups on the right
   (for example, *Banks* lists every bank-related database).
3. Open **CRSP** → **Stock / Security Files** → **Daily Stock File**.
4. Fill in the four steps of the query form:

| Step | What you choose | Advice |
|---|---|---|
| 1. Date range | Start and end dates | Daily data is large. Ask only for the period you need |
| 2. Company codes | Which firms | Enter tickers or PERMNOs, upload a list of codes, or search the entire database |
| 3. Variables | Which columns | Select only what your paper uses: for example date, PERMNO, price, return, volume |
| 4. Output | File format | Choose **csv**, with dates as `YYYY-MM-DD` |

5. Click **Submit Form**. A large query takes a few minutes.
6. When the status shows *success*, download the output file.

**Use PERMNO, not the ticker, to identify a stock.** Tickers change and are reused;
a PERMNO stays with the same security for its whole life.

---

## 3. Or query it from Python

For anything you will run more than once, a script is better than the website: it records
exactly what you asked for.

```bash
pip install wrds
```

```python
import wrds

db = wrds.Connection(wrds_username="your_username")   # asks for your password the first time

# what is available
db.list_libraries()
db.list_tables(library="crsp")

# daily data for Apple (PERMNO 14593), 2017
df = db.raw_sql("""
    select permno, date, prc, ret, vol
    from crsp.dsf
    where permno = 14593
      and date between '2017-01-01' and '2017-12-31'
""", date_cols=["date"])

db.close()
df.head()
```

**Never type your password into a notebook or a script.** Let `wrds.Connection` ask for it.
A password committed to GitHub stays in the history even after you delete the line.

---

## 4. Rules for your repository

WRDS data is licensed to NYCU. You may use it for your coursework; you may **not** pass it on.

- Keep downloaded files in `replicating-a-paper/data/rawdata/`, exactly as downloaded.
- Your course repository is **private**. Keep it that way while it holds WRDS data.
- Never put WRDS data in a public repository, a shared drive or a chat group.
- Commit the **query**: the script, or a note of the four form choices. A reader with their own
  WRDS account can then rebuild your data. That is what makes a replication reproducible.
- GitHub rejects files over 100 MB. For a large download, commit the query and a small sample.

In your R2 write-up, state the database, the table, the date range and the date you downloaded
the data.

---

Taiwan market data is in **TEJ**, which NYCU also subscribes to. Ask the teaching team if your
paper needs it.

# Journals to consider for your project

ML & FinTech · 115-1 · last updated 20260914

Your project replicates a high-quality paper. Part of doing that well is knowing **where work
like yours gets published**, because the outlet tells you what a field expects: how long the
paper is, how much theory it wants, whether code and data are required, and what counts as a
contribution.

Every journal below regularly publishes FinTech or quantitative finance work. General-purpose
journals that rarely touch finance have been left out.

Publisher sites block automated link checking, so open these in a browser; a link that looks
dead to a script is almost always fine. Several also require the NYCU VPN for full text.

`NSTC` is the tier from the 財會學門財務領域 report in `journal-ranking/2020 財務領域.pdf`.
A dash means the journal is not on that finance list, which is not a criticism — it usually
means the journal is an OR or CS outlet, and those are ranked elsewhere.

**Impact factor and quartile are deliberately not listed here.** They change every year, and a
stale number is worse than none when you are choosing where to submit. Look them up in Journal
Citation Reports through the NYCU VPN — see `journalranking.md` in this repository.

---

## 1. Finance and quantitative finance

Papers here lead with an economic question. The model is a tool, and a referee will ask
"so what for markets?" before asking about architecture.

| Journal | NSTC | Link |
|---|---|---|
| Finance Research Letters (FRL) | A– | https://www.sciencedirect.com/journal/finance-research-letters |
| International Review of Financial Analysis (IRFA) | A– | https://www.sciencedirect.com/journal/international-review-of-financial-analysis |
| The North American Journal of Economics and Finance (NAJEF) | — | https://www.sciencedirect.com/journal/the-north-american-journal-of-economics-and-finance |
| International Review of Economics & Finance (IREF) | A– | https://www.sciencedirect.com/journal/international-review-of-economics-and-finance |
| Quantitative Finance (QF) | ATier-2 | https://www.tandfonline.com/journals/rquf20 |
| Journal of Futures Markets (JFM) | ATier-2 | https://onlinelibrary.wiley.com/journal/10969934 |
| Pacific-Basin Finance Journal (PBFJ) | ATier-2 | https://www.sciencedirect.com/journal/pacific-basin-finance-journal |
| Finance and Stochastics | ATier-2 | https://link.springer.com/journal/780 |
| Journal of Risk | B+ | https://www.risk.net/journal-of-risk |
| Financial Innovation | — | https://jfin-swufe.springeropen.com/ |
| Digital Finance | — | https://link.springer.com/journal/42521 |
| Computational Economics | — | https://link.springer.com/journal/10614 |
| Insurance: Mathematics and Economics (IME) | — | https://www.sciencedirect.com/journal/insurance-mathematics-and-economics |

**Where to start.** FRL is the usual first target for a short empirical finance paper: it is
deliberately brief, turnaround is fast, and it publishes a lot of ML-in-finance work. NAJEF,
IRFA and IREF take longer papers. Financial Innovation and Digital Finance are the journals
built specifically for FinTech, and both are open access.

## 2. Operations research, with a finance stream

Papers here lead with a **method or a decision problem**. A referee wants to see that your
formulation is sound and that you compared against real alternatives.

| Journal | Link |
|---|---|
| European Journal of Operational Research (EJOR) | https://www.sciencedirect.com/journal/european-journal-of-operational-research |
| Annals of Operations Research | https://link.springer.com/journal/10479 |
| Decision Support Systems (DSS) | https://www.sciencedirect.com/journal/decision-support-systems |

**Note for credit-scoring projects.** EJOR is one of the most important outlets in the world for
credit scoring and bankruptcy prediction. If your paper is about classification on financial
data rather than about a market, this is often the right fit even though it is not a finance
journal.

## 3. Computer science and AI, with a finance stream

Papers here lead with the **model**. Benchmarks, ablation studies and reproducible code carry the
argument; the financial application can be the motivating case rather than the contribution.

| Journal | Link |
|---|---|
| Expert Systems with Applications (ESWA) | https://www.sciencedirect.com/journal/expert-systems-with-applications |
| Knowledge-Based Systems (KBS) | https://www.sciencedirect.com/journal/knowledge-based-systems |
| Applied Soft Computing | https://www.sciencedirect.com/journal/applied-soft-computing |
| Engineering Applications of Artificial Intelligence (EAAI) | https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence |
| Journal of Supercomputing (JSC) | https://link.springer.com/journal/11227 |

**Note.** ESWA is the highest-volume outlet for applied ML on financial data and the most common
landing place for a well-executed but not theoretically novel model. That is a feature for a
first paper, not a flaw.

---

## How to use this list

1. **Find your paper's journal first.** Look up the paper you are replicating and note where it
   was published. That journal, and its immediate neighbours in this list, are your reference
   point for what a finished version of your work looks like.
2. **Read the aims and scope page**, not just the title. Journals reject on scope more often
   than on quality.
3. **Match the category to your contribution.** If the interesting part is the finance question,
   section 1. If it is the formulation, section 2. If it is the model, section 3. Submitting a
   model paper to a finance journal is the most common avoidable mistake.
4. **Check the current impact factor and quartile yourself** in Journal Citation Reports, through
   the NYCU VPN. Do not trust a number copied from a slide or a list, including this one.
5. **Check tiers before you commit.** For work that will count toward departmental rewards, the
   NSTC 財務領域 tiers in `journal-ranking/` matter. Note that many strong ML-in-finance outlets
   are not on that list at all, so the methodologically right venue and the rewarded venue are
   not always the same journal. Decide which you are optimising for **before** you write.

## Finding reference papers

- **Google Scholar** — start from the paper you are replicating and use "Cited by" to find newer
  work, which is usually the fastest route to a literature review.
- **SSRN** (https://www.ssrn.com/) for finance working papers, often years ahead of publication.
- **arXiv q-fin** (https://arxiv.org/archive/q-fin) for the quantitative finance preprints.

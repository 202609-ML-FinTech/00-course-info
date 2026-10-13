# 202609-ML-FinTech — course information

Machine Learning and FinTech · 115-1 · Prof. Huei-Wen Teng
Department of Information Management and Finance, National Yang Ming Chiao Tung University

Public course materials for the course.

## Contents

- Syllabus and grading: **[202609-Machine-Learning-and-FinTech](https://timetable.nycu.edu.tw/?r=main/crsoutline&Acy=115&Sem=1&CrsNo=537707&lang=en-us)**.
- Student repositories live in this same organization, one per student, named `<STUDENTID>-<NICKNAME>`: 
- See **[list-of-repo.md](list-of-repo.md)**.


| Folder | Holds |
|---|---|
| `slides/` | Lecture slides, `yyyymmdd` prefixed |
| `in-class-exercise/` | In-class exercise worksheets and their data |
| `homework/` | Homework assignments, `HW-mmdd.md` |
| `python-cheatsheets/` | Python, NumPy and pandas cheat sheets |
| `journal-ranking/` | NSTC 財務領域 journal tiers and related ranking references |


## Textbook

James, Witten, Hastie, Tibshirani & Taylor, *An Introduction to Statistical Learning with Applications in Python* (ISLP), Springer, 2023.

- **[Download the PDF](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html)** — free, from the authors.
- [Book website](https://www.statlearning.com/) · [Python labs, data and code](https://www.statlearning.com/resources-python)


## E3

The grade records are posted on **E3**, not here. This repository is public, so it carries teaching materials only.

## Replicating a paper

Replicate one high-quality paper, individually, and deliver a manuscript and slides.



### Journal Ranking

Your selected paper must be from a journal from:
- the SCIE/SSCI list; check [Journal Citation Reports](https://jcr.clarivate.com/jcr/home) through the NYCU VPN for SCIE/SSCI edition)
- the list in **[journals-to-consider.md](journals-to-consider.md)** — journals for your project, grouped into finance, operations research, and computer science, with links and NSTC tiers <br>
- journals listed in the folder `journal-ranking/` for the NSTC 財會學門財務領域 tier report and related lists.
 

### Repo organization

Your own repository is `<STUDENTID>-<NICKNAME>`, private, in this organization.
Start it from **[00-repo-template](https://github.com/202609-ML-FinTech/00-repo-template)**
("Use this template"), which gives you the folders below. Its README has the full rules.

### Milestones

| Milestone | Content | Due |
|---|---|---|
| **R1** | Topic: introduce the paper, its motivation, and how it connects to your personal interests | Mon **10/05**, 23:59 |
| **R2** | Data: raw data, descriptions, EDA, and more | Mon **10/19**, 23:59 |
| **R3** | Benchmark model and experiment design, including ablation studies | Mon **11/09**, 23:59 |
| **R4** | Empirical analysis and conclusion | Mon **11/30**, 23:59 |

### Data

- **[WRDS guide](https://github.com/FIMA-Lab/00-research-toolkit/blob/main/WRDS-claude.md)** (FIMA Lab research toolkit) — get an NYCU WRDS account, download data, query from Python, licence rules, and what to do when your data is not on WRDS. Taiwan data: [TEJ guide](https://github.com/FIMA-Lab/00-research-toolkit/blob/main/TEJ-teng.md). Apply early: R2 is due 10/19.

### Templates

1. Manuscript — [Overleaf template](https://www.overleaf.com/read/gxnsffrpqgmj#145baa).
2. Slides — [Canva template](https://canva.link/jxzpkchh1kw5qpt), or
   **[20260920-template-ML&FinTech.pptx](20260920-template-ML&FinTech.pptx)** in this repository.

## Grading details 

### Homework (10%, 1% each)

Homework is assigned weekly and is due **7 days after it is assigned, at 23:59**.

- Week 2 (09/14): **[homework/HW-0914.md](homework/HW-0914.md)** — due 09/21 23:59.
- Week 3 (09/21): **[homework/HW-0921.md](homework/HW-0921.md)** — due 09/28 23:59.
- Week 6 (10/12): **[homework/HW-1012.md](homework/HW-1012.md)** — due 10/19 23:59.
- Week 7 (10/19): **[homework/HW-1019.md](homework/HW-1019.md)** — due 11/02 23:59.
- Week 9 (11/02): **[homework/HW-1102.md](homework/HW-1102.md)** — due 11/09 23:59.
- Week 10 (11/09): **[homework/HW-1109.md](homework/HW-1109.md)** — due 11/16 23:59.
- Week 11 (11/16): **[homework/HW-1116.md](homework/HW-1116.md)** — due 11/23 23:59.
- Week 12 (11/23): **[homework/HW-1123.md](homework/HW-1123.md)** — due 11/30 23:59.
- Week 13 (11/30): **[homework/HW-1130.md](homework/HW-1130.md)** — due 12/07 23:59.
- Week 14 (12/07): **[homework/HW-1207.md](homework/HW-1207.md)** — due 12/14 23:59.

### In-Class exercise (10%, 1% each)

In-Class exercise is due **by 12:10 at the lecture date**. Together, you need to submit a paper sheet to get point.  


| Week | Date | In-class exercise |
|---|---|---|
| 1 | 09/07 | MFS slides (design, upload to the Drive folder) |
| 2 | 09/14 | IC-0914: Python & EDA on the credit-default data, two parts |
| 3 | 09/21 | IC-0921: How diversified is your client, really? |
| 4 | 09/28 | no class (教師節) |
| 5 | 10/05 | IC-1005: Is this portfolio really two bets? |
| 6 | 10/12 | IC-1012: Is the manager's alpha real? |
| 7 | 10/19 | IC-1019: Approve this card? |
| 8 | 10/26 | no class (光復節補假) |
| 9 | 11/02 | IC-1102: Which cutoff? |
| 10 | 11/09 | IC-1109: Logistic or LDA? |
| 11 | 11/16 | IC-1116: Is the backtest honest? |
| 12 | 11/23 | IC-1123: Which of 40 factors do we keep? |
| 13 | 11/30 | IC-1130: Explain the rejection |
| 14 | 12/07 | no in-class exercise (R4 Q&A) |
| 15 | 12/14 | no in-class exercise (homework clinic) |
| 16 | 12/21 | Exam |


### Replicating a paper (30%) 

- MFS (3%)
- Fitness of the paper (2%): Ranking (35%), Finance (35%), Machine Learinng (30%) 
- R1 (5%): Manuscript (25%), Slides (25%), title, abstract, keywords, JEL codes, Motivations  
- R2 (5%)
- R3 (5%)
- R4 (5%)
- Cold calls presentations (5%) 

### Exam (50%)


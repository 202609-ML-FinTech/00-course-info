# 202609-ML-FinTech — course information

Machine Learning and FinTech · 115-1 · Prof. Huei-Wen Teng
Department of Information Management and Finance, National Yang Ming Chiao Tung University

Public course materials for the course. Student repositories live in this same
organization, one per student, named `<STUDENTID>-<NICKNAME>`: see **[list-of-repo.md](list-of-repo.md)**.

## Syllabus and grading

The grading policy is in the course syllabus on the NYCU course system:
**[202609-Machine-Learning-and-FinTech](https://timetable.nycu.edu.tw/?r=main/crsoutline&Acy=115&Sem=1&CrsNo=537707&lang=en-us)**.

## Textbook

James, Witten, Hastie, Tibshirani & Taylor, *An Introduction to Statistical Learning with Applications in Python* (ISLP), Springer, 2023.

- **[Download the PDF](https://hastie.su.domains/ISLP/ISLP_website.pdf.download.html)** — free, from the authors.
- [Book website](https://www.statlearning.com/) · [Python labs, data and code](https://www.statlearning.com/resources-python)

## Contents

| Folder | Holds |
|---|---|
| `slides/` | Lecture slides, `yyyymmdd` prefixed |
| `in-class-exercise/` | In-class exercise worksheets and their data |
| `homework/` | Homework assignments, `HW-mmdd.md` |
| `python-cheatsheets/` | Python, NumPy and pandas cheat sheets |
| `journal-ranking/` | NSTC 財務領域 journal tiers and related ranking references |

## E3

The grade records are posted on **E3**,
not here. This repository is public, so it carries teaching materials only.

## Journal Ranking

- **[journals-to-consider.md](journals-to-consider.md)** — journals for your project, grouped into finance, operations research, and computer science, with links and NSTC tiers. 
- Go to the [Journal Citation Reports](https://jcr.clarivate.com/jcr/home) through the NYCU VPN.
- See `journal-ranking/` for the NSTC 財會學門財務領域 tier report and related lists.

## Repo organization

Your own repository is `<STUDENTID>-<NICKNAME>`, private, in this organization.
Start it from **[00-repo-template](https://github.com/202609-ML-FinTech/00-repo-template)**
("Use this template"), which gives you the folders below. Its README has the full rules.

| Folder | What goes in it |
|---|---|
| `homework/<mmdd>/` | One folder per homework, named by the date it was assigned |
| `in-class-exercise/<mmdd>/` | One folder per class |
| `replicating-a-paper/data/rawdata/` | Data exactly as downloaded — never edited |
| `replicating-a-paper/data/processed-data/` | What your code produces from rawdata |
| `replicating-a-paper/coding/` | Notebooks and scripts |
| `replicating-a-paper/_snapshots/` | The paper you are replicating, and its slides |

The commit timestamp is your submission time. A file saved but not pushed is not submitted.

## Replicating a paper

Replicate one high-quality paper, individually, and deliver a manuscript and slides.

### Milestones

| Milestone | Content | Due |
|---|---|---|
| **R1** | Topic: introduce the paper, its motivation, and how it connects to your personal interests | Mon **10/05**, 23:59 |
| **R2** | Data: raw data, descriptions, EDA, and more | Mon **10/19**, 23:59 |
| **R3** | Benchmark model and experiment design, including ablation studies | Mon **11/09**, 23:59 |
| **R4** | Empirical analysis and conclusion | Mon **11/30**, 23:59 |

### Data

- **[wrds-guide.md](wrds-guide.md)** — how to get an NYCU WRDS account and download data (CRSP, Compustat and more). Apply early: R2 is due 10/19.

### Templates

1. Manuscript — [Overleaf template](https://www.overleaf.com/read/gxnsffrpqgmj#145baa).
2. Slides — [Canva template](https://canva.link/jxzpkchh1kw5qpt), or
   **[20260920-template-ML&FinTech.pptx](20260920-template-ML&FinTech.pptx)** in this repository.

## In-Class exercise

Each in-class exercise is due at **12:10 on the day of class**.

- Week 1 (09/07): Design your FMS slides and upload them to the [Google Drive folder](https://drive.google.com/drive/folders/1OS2a4swz2FfiPXWjLn2di5DQFn5AKYqa?usp=sharing), named `<STUDENTID>-<NICKNAME>.pdf` (example: `415707006-Jerry.pdf`). Due 09/07 12:10.
- Week 2 (09/14): **[in-class-exercise/IC-0914.ipynb](in-class-exercise/IC-0914.ipynb)** — due 09/14 12:10.
- Week 3 (09/21): **[in-class-exercise/IC-0921.ipynb](in-class-exercise/IC-0921.ipynb)** — due 09/21 12:10.
- Week 5 (10/05): **[in-class-exercise/IC-1005.ipynb](in-class-exercise/IC-1005.ipynb)** — due 10/05 12:10.
- Week 6 (10/12): **[in-class-exercise/IC-1012.ipynb](in-class-exercise/IC-1012.ipynb)** — due 10/12 12:10.
- Week 7 (10/19): **[in-class-exercise/IC-1019.ipynb](in-class-exercise/IC-1019.ipynb)** — due 10/19 12:10.
- Week 9 (11/02): **[in-class-exercise/IC-1102.ipynb](in-class-exercise/IC-1102.ipynb)** — due 11/02 12:10.
- Week 10 (11/09): **[in-class-exercise/IC-1109.ipynb](in-class-exercise/IC-1109.ipynb)** — due 11/09 12:10.
- Week 11 (11/16): **[in-class-exercise/IC-1116.ipynb](in-class-exercise/IC-1116.ipynb)** — due 11/16 12:10.
- Week 12 (11/23): **[in-class-exercise/IC-1123.ipynb](in-class-exercise/IC-1123.ipynb)** — due 11/23 12:10.
- Week 13 (11/30): **[in-class-exercise/IC-1130.ipynb](in-class-exercise/IC-1130.ipynb)** — due 11/30 12:10.

## Homework

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


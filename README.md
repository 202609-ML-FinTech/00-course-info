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
| `in-class-exercise/` | Case-study notebooks and their data |
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

Each homework is due **7 days after it is assigned, at 23:59** (14 days when a holiday falls between). There are 10.

| # | Assigned | Homework | ISLP exercises | Due |
|---|---|---|---|---|
| 1 | 09/14 | [HW-0914](homework/HW-0914.md) | Ch2 Q2, Q3, Q7 and more (see file) | 09/21 |
| 2 | 09/21 | [HW-0921](homework/HW-0921.md) | see file | 09/28 |
| 3 | 10/12 | [HW-1012](homework/HW-1012.md) | Ch12 Q10; Ch3 Q9, Q15 | 10/19 |
| 4 | 10/19 | [HW-1019](homework/HW-1019.md) | Ch4 Q6, Q9 | 11/02 |
| 5 | 11/02 | [HW-1102](homework/HW-1102.md) | Ch4 Q12, Q13(a–d) | 11/09 |
| 6 | 11/09 | [HW-1109](homework/HW-1109.md) | Ch4 Q13(e–j), Q14, Q15 | 11/16 |
| 7 | 11/16 | [HW-1116](homework/HW-1116.md) | Ch5 Q8, Q9; Ch6 Q8, Q9(a–d) | 11/23 |
| 8 | 11/23 | [HW-1123](homework/HW-1123.md) | Ch7 Q6; Ch8 Q4 | 11/30 |
| 9 | 12/07 | [HW-1207](homework/HW-1207.md) | Ch8 Q8 | 12/14 |
| 10 | 12/14 | [HW-1214](homework/HW-1214.md) | Ch10 Q1, Q6 | 12/21 |

### Case study (11%, 1% each)

Case studies (previously called in-class exercises) are due **by 12:10 on the lecture day**. Each pair hands in one paper sheet. Hand it in and you get full credit for that case study: the point is to think in class. There are 11.

| # | Date | Case study |
|---|---|---|
| 1 | 09/14 | Python & EDA on the credit-default data |
| 2 | 09/21 | How diversified is your client, really? |
| 3 | 10/05 | Is this portfolio really two bets? |
| 4 | 10/12 | Is the manager's alpha real? |
| 5 | 10/19 | Approve this card? |
| 6 | 11/02 | Two categories, then three |
| 7 | 11/09 | Logistic or LDA? |
| 8 | 11/16 | Is the backtest honest? Which of 40 factors do we keep? |
| 9 | 11/23 | Explain the rejection |
| 10 | 12/07 | A tree, a forest or boosting? |
| 11 | 12/14 | Does the network earn its complexity? |

No case study on 09/28, 10/26 and 11/30 (no class), or on 12/21 (exam).

### Video presentation (4%): no class on 11/30

Prof. Teng will be at a conference at the European Central Bank, Frankfurt, Germany. There is no class on Mon **11/30**, and you do not need to come to the classroom. You still work on that day.

**Your video.** Use your slides to present your understanding of the paper you are replicating, in **10–15 minutes**. Show your face. Cover:

1. Motivation
2. Data
3. Benchmark and experiment design
4. Conclusion

**Submit by Mon 11/23, 13:59.** Upload the video to YouTube and add the link to the `README.md` of your own repository. That is your submission. Public is best; unlisted is fine. Do not choose "private": a private YouTube video will not play for anyone else.

**Feedback by Mon 11/30, 12:10.** You will be assigned **10 videos** to watch. Give your feedback on these 10 videos through the Google form announced on E3.

### Replicating a paper (29%) 

- MFS (3%)
- Fitness of the paper (2%): Ranking (35%), Finance (35%), Machine Learning (30%) 
- R1 (5%): Manuscript (25%), Slides (25%), title, abstract, keywords, JEL codes, Motivations  
- R2 (5%)
- R3 (5%)
- R4 (5%)
- Video presentation (4%)

### Exam (50%)

- Mon **12/21**, in class, 80 minutes.
- 24 multiple-choice questions, five options each, two to four correct. Choose all correct options; each option is scored, so a partly right answer earns partial credit.
- Covers Ch2–8 and Ch12; Ch10 conceptual only.
- One A4 formula sheet allowed.

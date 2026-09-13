# Journals to consider for your project

ML & FinTech · 115-1 · last updated 20260914

Your project replicates a high-quality paper. Part of doing that well is knowing **where work
like yours gets published**, because the outlet tells you what a field expects: how long the
paper is, how much theory it wants, whether code and data are required, and what counts as a
contribution.

This list is grounded in where four faculty working in this area actually publish:
**鄧惠文 (Huei-Wen Teng)**, **戴天時 (Tian-Shyr Dai)**, **黃思皓 (Szu-Hao Huang)** — all in
資訊管理與財務金融學系, NYCU — and **吳牧恩 (Mu-En Wu)**, 資訊與財金管理系, NTUT.

The initial in the **Seen in** column shows whose publication record the journal appears in:
**T** Teng · **D** Dai · **H** Huang · **W** Wu. Blank means it is a standard outlet in the
category but was not verified against one of these four.

Publisher sites block automated link checking, so open these in a browser; a link that looks
dead to a script is almost always fine. Several also require the NYCU VPN for full text.

`NSTC` is the tier from the 財會學門財務領域 report in `journal-ranking/2020 財務領域.pdf`.
A dash means the journal is not on that finance list, which is not a criticism — it usually
means the journal is an OR or CS outlet, and those are ranked elsewhere.

---

## 1. Finance journals

Papers here lead with an economic question. The model is a tool, and a referee will ask
"so what for markets?" before asking about architecture.

| Journal | NSTC | Seen in | Link |
|---|---|---|---|
| Finance Research Letters (FRL) | A– | T | https://www.sciencedirect.com/journal/finance-research-letters |
| International Review of Financial Analysis (IRFA) | A– | T | https://www.sciencedirect.com/journal/international-review-of-financial-analysis |
| North American Journal of Economics and Finance (NAJEF) | — | T | https://www.sciencedirect.com/journal/the-north-american-journal-of-economics-and-finance |
| Quantitative Finance (QF) | ATier-2 | T, D | https://www.tandfonline.com/journals/rquf20 |
| Journal of Futures Markets (JFM) | ATier-2 | D | https://onlinelibrary.wiley.com/journal/10969934 |
| Pacific-Basin Finance Journal (PBFJ) | ATier-2 | — | https://www.sciencedirect.com/journal/pacific-basin-finance-journal |
| Finance and Stochastics | ATier-2 | T | https://link.springer.com/journal/780 |
| Journal of Risk | B+ | T | https://www.risk.net/journal-of-risk |
| International Review of Economics and Finance (IREF) | A– | T | https://www.sciencedirect.com/journal/international-review-of-economics-and-finance |
| Insurance: Mathematics and Economics (IME) | — | T | https://www.sciencedirect.com/journal/insurance-mathematics-and-economics |
| Financial Innovation | — | T | https://jfin-swufe.springeropen.com/ |
| Digital Finance | — | T | https://link.springer.com/journal/42521 |
| Computational Economics | — | T, W | https://link.springer.com/journal/10614 |
| Review of Pacific Basin Financial Markets and Policies | — | T | https://www.worldscientific.com/worldscinet/rpbfmp |
| Journal of the Chinese Statistical Association (JCSA) | — | T | https://www.stat.org.tw/ |

**Where to start.** FRL is the usual first target for a short empirical finance paper: it is
deliberately brief, turnaround is fast, and it publishes a lot of ML-in-finance work. NAJEF and
IRFA take longer papers. Financial Innovation and Digital Finance are the natural homes for
FinTech-specific work and are open access.

## 2. Operations research and management science

Papers here lead with a **method or a decision problem**. A referee wants to see that your
formulation is sound and that you compared against real alternatives.

| Journal | Seen in | Link |
|---|---|---|
| European Journal of Operational Research (EJOR) | — | https://www.sciencedirect.com/journal/european-journal-of-operational-research |
| Annals of Operations Research | — | https://link.springer.com/journal/10479 |
| Omega | — | https://www.sciencedirect.com/journal/omega |
| Decision Support Systems (DSS) | — | https://www.sciencedirect.com/journal/decision-support-systems |
| Knowledge-Based Systems (KBS) | W | https://www.sciencedirect.com/journal/knowledge-based-systems |
| Engineering Optimization | W | https://www.tandfonline.com/journals/geno20 |
| Quality Technology & Quantitative Management | W | https://www.tandfonline.com/journals/ttqm20 |

**Note for credit-scoring projects.** EJOR is one of the most important outlets in the world for
credit scoring and bankruptcy prediction. If your paper is about classification on financial
data rather than about a market, this is often the right fit even though it is not a finance
journal.

## 3. Computer science, AI and expert systems

Papers here lead with the **model**. Benchmarks, ablation studies and reproducible code carry the
argument; the financial application can be the motivating case rather than the contribution.

| Journal | Seen in | Link |
|---|---|---|
| Expert Systems with Applications (ESWA) | W | https://www.sciencedirect.com/journal/expert-systems-with-applications |
| Applied Soft Computing | W | https://www.sciencedirect.com/journal/applied-soft-computing |
| Information Sciences | W | https://www.sciencedirect.com/journal/information-sciences |
| Information Fusion | H | https://www.sciencedirect.com/journal/information-fusion |
| Engineering Applications of Artificial Intelligence (EAAI) | H | https://www.sciencedirect.com/journal/engineering-applications-of-artificial-intelligence |
| Pattern Recognition | H | https://www.sciencedirect.com/journal/pattern-recognition |
| IEEE Transactions on Knowledge and Data Engineering (TKDE) | H | https://www.computer.org/csdl/journal/tk |
| Journal of Supercomputing (JSC) | W | https://link.springer.com/journal/11227 |
| Neural Computing and Applications | W | https://link.springer.com/journal/521 |
| Applied Intelligence | W | https://link.springer.com/journal/10489 |
| IEEE Access | W | https://ieeeaccess.ieee.org/ |

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
4. **Check tiers before you commit.** For work that will count toward departmental rewards, the
   NSTC 財務領域 tiers in `journal-ranking/` matter. Note that many strong ML-in-finance outlets
   are not on that list at all, so the methodologically right venue and the rewarded venue are
   not always the same journal. Decide which you are optimising for **before** you write.
5. **Journal Citation Reports** for impact factors and quartiles: see `journalranking.md`
   in this repository. Access is through the NYCU VPN.

## Finding reference papers

- **Google Scholar** — start from the paper you are replicating and use "Cited by" to find newer
  work, which is usually the fastest route to a literature review.
- **The four faculty above** all have public profiles; their recent papers are a good sample of
  what this kind of project looks like when finished.
- **SSRN** (https://www.ssrn.com/) for finance working papers, often years ahead of publication.
- **arXiv q-fin** (https://arxiv.org/archive/q-fin) for the quantitative finance preprints.

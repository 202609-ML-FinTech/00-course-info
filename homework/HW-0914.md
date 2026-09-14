# Homework 0914

ML & FinTech · 115-1 · assigned 20260914 · due: to be announced on E3

Source: *An Introduction to Statistical Learning with Applications in Python* (ISLP),
James et al. (2023), **§2.4 Exercises 2, 3, 7 and 8**. The book is in this repository as
[`james2023introduction.pdf`](../james2023introduction.pdf). Read the full wording of each
question there; the summaries below tell you what is expected and how it is graded.

You may use any AI tool. What is graded is your judgement, not your syntax.

---

## Q2 · Conceptual — what kind of problem is it?

The exercise describes three scenarios. For **each** one, state:

1. **Classification or regression**, and why in one sentence.
2. **Inference or prediction** — are we trying to understand a relationship, or to forecast an outcome?
3. **n** (number of observations) and **p** (number of predictors), as numbers.

A table with one row per scenario is the expected format.

## Q3 · Conceptual — the bias–variance decomposition

**(a) Sketch** squared bias, variance, training error, test error and the irreducible (Bayes)
error on one plot, against model flexibility.

- **Draw it by hand and upload a photograph.** A generated, plotted or copied figure earns no marks.
- Label both axes and all five curves.

**(b) Explain** why each of the five curves has the shape you drew — one short paragraph per curve.
**Most of the credit for Q3 is here.** Say, in particular, why the test error is U-shaped and why
the training error can fall below the irreducible error.

## Q7 · By hand — K-nearest neighbours

The exercise gives six observations with three predictors and a class label, and a test point at
X₁ = X₂ = X₃ = 0.

(a) Compute the Euclidean distance from each observation to the test point. Show the working.
(b) Predict the class with **K = 1**, and say which observation decides it.
(c) Predict the class with **K = 3**, and say which observations decide it.
(d) If the Bayes decision boundary is highly non-linear, should the best K be large or small? Justify.

Work this out by hand (a photo or typed working is fine). You may check your numbers with code afterwards.

## Q8 · Applied — exploring the `College` data

Load the `College` data set and complete parts **(a)–(h)** as set out in the book:
reading the data, fixing the index, `describe()`, a scatterplot matrix, boxplots, creating the
`Elite` variable, histograms, and a final open exploration.

Submit a Jupyter notebook that **runs top to bottom from a fresh kernel**.

**Part (h) carries most of the weight of Q8.** Write:

- **one claim** about the data that could turn out to be wrong (a number, a comparison, or a direction), and
- **the single figure** that supports it, with two or three sentences explaining why it supports the claim.

A tour of `describe()` output, or a list of "insights", is not a finding and earns little credit.

---

## What to submit

Put everything in the `homework/` folder of **your own** repository, named with the date:

| File | Contents |
|---|---|
| `HW-0914.pdf` or `HW-0914.md` | Answers to Q2, Q3(b), Q7 |
| `HW-0914-Q3a.jpg` | Photograph of your hand-drawn Q3(a) sketch |
| `HW-0914-Q8.ipynb` | The notebook for Q8 |

Commit and push before the deadline announced on E3. The time of your last push counts.

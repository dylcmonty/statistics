# sprg-26

## Repository Naming Convention

This repository uses a compact file naming pattern so course material can be found by date, course, artifact type, version, and document role.

Canonical pattern:

```text
<YYYY-MM-DD>-<course_id>-<artifact_id>-<version>[-<role>].<ext>
```

Current examples:

```text
hw/2026-00-00-stat_461-hw_1-0.0-0-sub.tex
hw/2026-00-00-stat_461-hw_6-0.0-0-sub.tex
leaflets/2026-00-00-stat_461-exam_1-0-sol.tex
leaflets/2026-00-00-stat_461-exam_3-0-sol.tex
leaflets/2026-00-00-stat_461-final-0.tex
leaflets/2026-00-00-stat_461-final-0-sol.tex
leaflets/2025-00-00-stat_461-ch_7_8-0-sol.tex
```

Field meanings:

```text
YYYY-MM-DD   Calendar date. Use 00 for unknown or general month/day placeholders.
course_id    Lowercase course identifier, e.g. stat_461.
artifact_id  Assignment or content unit, e.g. hw_6, exam_3, final, ch_7_8.
version      Numeric variant/index. Start at 0; use decimals only when a sub-version is needed.
role         Optional document role.
ext          File type, usually tex or pdf.
```

Role suffixes:

```text
(no suffix)  Prompt, exam, worksheet, or source content.
-sol         Solution file or answer key.
-sub         Submission-ready homework file.
```

Directory usage:

```text
hw/          Homework files.
leaflets/    Exams, finals, chapter packets, practice sheets, and solution leaflets.
```

Agent recall rules:

```text
Homework N            Search: hw/ + stat_461-hw_N
Exam N solutions      Search: leaflets/ + stat_461-exam_N + -sol
Final questions       Search: leaflets/ + stat_461-final-0.tex
Final solutions       Search: leaflets/ + stat_461-final + -sol
Chapter A-B solutions Search: leaflets/ + stat_461-ch_A_B + -sol
```

When multiple files match, prefer the exact year first, then the exact artifact id, then the most specific role suffix. Do not treat a `-sol` file as the source exam/question file unless the request is explicitly asking for solutions.

---

## Homework

Homework-1: 1.1–1.3
Homework-2: 2.1–2.5
Homework-3: 3.1-4.2
Homework-4: 4.3–5.5
Homework-5: 6.1–7.4
Homework-6: 8.3–9.4

---

## Test

Exam-1: HERE
Exam-2: HERE
Exam-3: HERE
Exam-4: 1-10 ~ Final

---

## Chapters

1. 
1.1 Descriptive (pictorial/tabular)
1.2 Location
1.3 Variability

2. 
2.1. Sample Spaces and Events
2.2. Axioms, Interpretations, and Properties of Probability
2.3. Counting Techniques
2.4. Conditional Probability
2.5. Independence

3. Discrete Random Variables and Probability Distributions
3.1 Random Variables
3.2 Probability Distributions for Discrete Random Variables
3.3 Expected Values, 3.4 The Binomial Probability Distribution
3.5 Hypergeometric and Negative Binomial Distributions
3.6 The Poisson Probability Distribution

4. Continuous Random Variables and Probability Distributions
4.1 Probability Density Functions
4.2 Cumulative Distribution Functions and Expected Values
4.3 The Normal Distribution
4.4 The Exponential and Gamma Distributions
4.5 Other Continuous Distributions

5. Joint Probability Distributions and Random Samples
5.1 Jointly Distributed Random Variables
5.2 Expected Values, Covariance, and Correlation
5.3 Statistics and Their Distributions
5.4 The Distribution of the Sample Mean
5.5 The Distribution of a Linear Combination)

6. Point Estimation
6.1 General Concepts of Point Estimation
6.2 Methods of Point Estimation

7. Statistical Intervals Based on a Single Sample
7.1 Basic Properties of Confidence Intervals
7.2 Large-Sample Confidence Intervals for a Population Mean and Proportion
7.3 Intervals Based on a Normal Population Distribution
7.4 Confidence Intervals for the Variance and Standard Deviation of a Normal Population)

8. Tests of Hypotheses Based on a Single Sample
8.1. Hypotheses and Test Procedures
8.2. Z Tests for Hypotheses about a Population Mean
8.3. The One-Sample t Test
8.4. Tests Concerning a Population Proportion

9. Inferences Based on Two Samples
9.1. Z Tests and Confidence Intervals for a Difference Between Two Population Means
9.2. The Two-Sample t Test and Confidence Interval
9.3. Analysis of Paired Data
9.4. Inferences Concerning a Difference Between Population Proportions

10. The Analysis of Variance & ANOVA

---

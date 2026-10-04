# ASA DataFest 2024 — Optimal Question Types for Learning Outcomes

**Finalist | Team Lead | ASA DataFest 2024**

This project investigates how different types of interactive questions are associated with student learning outcomes in online statistics education.

Our team analysed student interaction and assessment data from CourseKata, an online statistics and data science learning platform, with the goal of identifying which question formats appear most effective for improving end-of-chapter performance.

The project was completed as part of **ASA DataFest 2024**, where our team was selected as a finalist.

Official UCLA DataFest results:  
http://datafest.stat.ucla.edu/past-datafests/results/

---

## Research Question

How should an interactive statistics textbook balance different question types to support stronger learning outcomes?

We focused on four major question formats:

- Multiple choice
- Short text
- Association
- Choice matrix

We compared student performance across these formats and examined how success on each question type related to subsequent end-of-chapter assessment performance.

---

## Methods

The analysis included:

- Data cleaning and feature construction
- Student-level aggregation of question performance
- Exploratory data analysis and visualisation
- Correlation analysis between question-type performance and learning outcomes
- Regression modelling
- Ridge regression with cross-validation
- Interaction effects between question types
- Dominance analysis
- Shapley-value decomposition for relative predictor importance
- Model-based estimation of an optimal question-type composition

---

## Key Idea

Rather than focusing only on whether students answered questions correctly, we investigated whether performance on different **types of questions** was differently associated with later learning outcomes.

This allowed us to estimate the relative contribution of each question format and explore whether the current distribution of question types could be improved.

---

## Results

Our analysis found substantial differences in the relationship between question format and end-of-chapter performance.

The final modelling stage used regularised regression to compare question types while accounting for correlation and interaction effects between them.

We then used variable-importance methods, including dominance analysis and Shapley-style decomposition, to assess the relative contribution of each question type to observed learning outcomes.

The results suggested that the optimal mix of question formats may differ considerably from the existing distribution used in the learning material.

---

## Competition Outcome

**ASA DataFest 2024 Finalist**

I served as **Team Lead** for the project.

DataFest is a large-scale data science competition in which teams analyse a complex real-world dataset and develop an actionable recommendation within a limited time period.

Our final presentation focused on:

> **The Optimal Question Types for Learning Outcomes**

---

## Repository Contents

```text
.
├── README.md
├── presentation/
│   └── DataFest_2024_The_Decoders.pdf
└── figures/
    └── selected_results.png

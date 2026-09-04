# Project 2 — Model-Readiness Analysis

## Purpose

In the Week 2 demo and lab, you practiced examining a dataset for model readiness. In this project, you will apply that workflow more independently to a different dataset.

You may use the Week 2 demo and lab as references, but this project will not tell you exactly which columns to inspect or which plots to create. Your job is to decide what evidence is useful.

The goal is **not** to clean the dataset yet. Your goal is to identify and document what could affect a specified machine-learning workflow.

> **Finding first. Fix later.**

---

## Scenario

A Portuguese banking institution conducted direct-marketing campaigns by telephone. The supplied classification task is to predict whether a client will subscribe to a term deposit.

**Target:** `y`

The project uses an instructional version of the UCI Bank Marketing dataset. The original dataset is real and publicly documented. A small number of data-quality and representation issues have been intentionally introduced for this course project.

Your task is to find and document issues that could affect the supplied classification workflow.

---

## Dataset

Use:

```text
bank_marketing_project2.csv
```

Do not modify the original CSV file.

Read `DATA_SOURCE.md` before beginning your analysis.

---

## What to Submit

Submit your completed Project 2 notebook through the Classroom 50 / GitHub workflow established in Week 1.

Your notebook should:

- run from top to bottom without errors,
- contain the code and outputs that support your conclusions,
- use markdown to explain your reasoning,
- include a completed model-readiness report,
- include a concise final readiness statement.

---

# Required Work

## 1. Understand the Modeling Task

In your own words, explain:

- what the classification workflow is intended to predict,
- what the target represents,
- what one row appears to represent.

---

## 2. Review the Dataset

Perform an initial inspection of the dataset.

Your inspection should be sufficient to understand:

- its size,
- its columns,
- stored data types,
- missingness,
- general numerical and categorical characteristics.

Do not just produce output. Explain anything that appears relevant to model readiness.

---

## 3. Identify Target and Candidate Features

Identify:

- the target,
- plausible candidate features,
- any fields that may require special treatment,
- any fields whose role or meaning needs clarification.

Remember that a pandas data type does not automatically determine a feature's modeling role.

---

## 4. Investigate Model-Readiness Concerns

Use appropriate pandas operations, summaries, filtering, and visualizations to investigate the data.

You decide what deserves closer inspection.

Your analysis should consider areas such as:

- missing values,
- inconsistent categorical values,
- incompatible or suspicious representations,
- unusual numerical values,
- feature roles,
- the target distribution,
- other characteristics that could affect a scikit-learn classification workflow.

You are **not** being told how many problems exist or exactly where they are.

Do not assume that every unusual value is invalid.

---

## 5. Create Focused Evidence

Include at least:

- **two targeted summaries or inspections**, and
- **two purposeful visualizations**.

For each visualization, explain what question it helps answer.

Quality is more important than quantity.

---

## 6. Review Provenance and Documentation

Using `DATA_SOURCE.md`, document:

- where the original data came from,
- the purpose of the original dataset,
- one fact from the source documentation that affects how you interpret a field,
- one limitation, uncertainty, or assumption that should be documented.

---

## 7. Model-Readiness Report

Document at least **five meaningful findings** using this structure:

| Finding | Evidence | Impact on Workflow | Next Step |
|---|---|---|---|
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |

Your evidence should come from output produced in your notebook.

Your next step may be:

- prepare or transform the data later,
- investigate further,
- verify documentation,
- leave the value unchanged if there is not enough evidence to justify changing it.

---

## 8. Final Readiness Statement

Write a concise professional conclusion that answers:

1. Is the dataset ready to use as-is for the supplied classification workflow?
2. What are the highest-priority preparation needs?
3. What requires further investigation before a change should be made?

---

-
## Repository Workflow

1. Open the Project 2 Classroom 50 link.
2. Accept the project.
3. Clone the repository into your main course folder.
4. Use the shared course `.venv` from Week 1.
5. Complete the notebook.
6. Run the notebook from top to bottom and verify that it works.
7. Commit and push your work.
8. Verify the completed notebook in the online repository.
9. Submit the repository link in Blackboard.

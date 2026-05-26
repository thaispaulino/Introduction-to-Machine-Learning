# Introduction to Machine Learning - Megaline Plan Recommendation

## Project Overview

This project is part of the **TripleTen Data Science Bootcamp**. The goal is to build a machine learning classification model that recommends one of Megaline's two newer plans — **Smart** or **Ultra** — to subscribers who are still using legacy plans.

The model is trained on behavioral data from subscribers who have already switched, and the objective is to achieve an accuracy of at least **75%** on the test set.

---

## Dataset

**File:** `users_behavior.csv` — 3,214 rows x 5 columns

| Column | Description |
|--------|-------------|
| `calls` | Number of calls made |
| `minutes` | Total call duration (minutes) |
| `messages` | Number of text messages sent |
| `mb_used` | Internet traffic used (MB) |
| `is_ultra` | Target: 1 = Ultra plan, 0 = Smart plan |

The data was split into **training**, **validation**, and **test** sets.

---

## Models Explored

| Model | Validation Accuracy |
|-------|---------------------|
| Decision Tree | — |
| Logistic Regression | ~72.3% |
| **Random Forest** | **~77.4%** |

Hyperparameter tuning was applied to `n_estimators` (1–10) to find the best Random Forest configuration.

---

## Results

**Best model:** Random Forest with `n_estimators=8`

**Test accuracy: 80.09%** — exceeding the 75% project requirement

---

## Tech Stack

- Python 3
- - Pandas
  - - Scikit-learn
    - - Jupyter Notebook
     
      - ---

      ## Repository Structure

      ```
      ├── notebook (1).ipynb       # Main analysis and model training
      ├── users_behavior.csv       # Dataset (3,214 users)
      ├── .gitignore
      └── README.md
      ```

      ---

      ## Author

      **Thais Paulino** — Data Analyst transitioning into Data Science

      [LinkedIn](https://www.linkedin.com/in/thais-paulino-9942a260)

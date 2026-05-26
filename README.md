📱—📌——🗂️—×🧠—✅–✅—🎉🛠️📁├──├──├──└──👩‍#💻— 📱 Introduction to Machine Learning — Megaline Plan Recommendation

## 📌 Project Overview

This project is part of the **TripleTen Data Science Bootcamp**. The goal is to build a machine learning classification model that recommends one of Megaline's two newer plans — **Smart** or **Ultra** — to subscribers who are still using legacy plans.

The model is trained on behavioral data from subscribers who have already switched, and the objective is to achieve an accuracy of at least **0.75** on the test set.

---

## 🗂️ Dataset

The following CSV files contain monthly usage data per subscriber:

| File | Description |
|------|-------------|
| `megaline_users.csv` | User info and current plan |
| `megaline_plans.csv` | Plan details (Smart vs Ultra) |
| `megaline_calls.csv` | Number and duration of calls |
| `megaline_messages.csv` | Number of text messages sent |
| `megaline_internet.csv` | Internet traffic used (MB) |

**Target variable:** `is_ultra` — 1 if the subscriber uses the Ultra plan, 0 for Smart.

---

## 🧠 Models Explored

- Decision Tree Classifier
- - Random Forest Classifier
  - - Logistic Regression
   
    - Hyperparameter tuning was applied to find the best-performing model configuration.
   
    - ---

    ## ✅ Results

    The best model achieved an accuracy above the **0.75 threshold** on the test set using a **Random Forest** classifier.

    ---

    ## 🛠️ Tech Stack

    - Python 3
    - - Pandas
      - - Scikit-learn
        - - Jupyter Notebook
         
          - ---

          ## 📁 Repository Structure

          ```
          ├── notebook.ipynb           # Main analysis and model training
          ├── megaline_users.csv
          ├── megaline_plans.csv
          ├── megaline_calls.csv
          ├── megaline_messages.csv
          ├── megaline_internet.csv
          └── README.md
          ```

          ---

          ## 👩‍💻 Author

          **Thais Paulino** — Data Analyst transitioning into Data Science
          [LinkedIn](https://www.linkedin.com/in/thais-paulino-9942a260)

# 🚀 Introvert vs Extrovert Prediction 😊

A lightweight Kaggle Playground challenge to classify individuals as **Introvert** or **Extrovert** based on social behavior and personality traits.

---

## 🎯 Competition Overview

* **Objective**: Predict the `Personality` label (`Introvert` or `Extrovert`) for each person in the test set.

* **Evaluation Metric**: Accuracy score compared to the ground-truth labels.

* **Timeline**:

  * Start: June 30, 2025
  * Submission Deadline: July 31, 2025, 11:59 PM UTC

---

## 📊 Data Description

| File                    | Rows   | Columns                                | Purpose                     |
| ----------------------- | ------ | -------------------------------------- | --------------------------- |
| `train.csv`             | 18,524 | `id`, 7 feature columns, `Personality` | Model training              |
| `test.csv`              | 6,175  | `id`, 7 feature columns                | Predictions (labels hidden) |
| `sample_submission.csv` | 6,175  | `id`, `Personality`                    | Submission format example   |

### ✨ Features

* **Time_spent_Alone**: Hours per day spent alone (numeric)

* **Stage_fear**: Public speaking anxiety (`Yes`/`No`)

* **Social_event_attendance**: Frequency of attending events (numeric)

* **Going_outside**: Days per week going outside (numeric)

* **Drained_after_socializing**: Feeling drained after socializing (`Yes`/`No`)

* **Friends_circle_size**: Number of close friends (numeric)

* **Post_frequency**: Social media post frequency (numeric)

---

## 🛠️ Baseline Model

A simple pipeline to get you started:

1. **Preprocessing** 🧹

   * Encode binary features (`Yes`/`No`) as 0/1
   * Impute missing values (median or most frequent)

2. **Modeling** 🤖

   * Logistic Regression or Random Forest
   * Cross-validate to tune hyperparameters

3. **Submission** 📄

   * Predict labels for `test.csv`
   * Save to CSV in the required format.

---

## 📁 Project Structure

```
├── data/
│   ├── train.csv
│   ├── test.csv
│   └── sample_submission.csv
├── notebooks/            # EDA, Data processing and model scripts
├── requirements.txt      # Python dependencies
└── README.md             # Project overview and instructions
```

---

## 📜 License

This project is released under the MIT License. 🎉

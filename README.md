# 🧠 Personality Prediction – Kaggle Playground Series S5E7

This repository contains my solution for the Kaggle competition **"Predict the Introverts from the Extroverts"** (Playground Series - Season 5, Episode 7).

🔗 **Competition Link:** [Kaggle](https://www.kaggle.com/competitions/playground-series-s5e7)

---

## 📌 Project Overview

The task was to build a machine learning model to predict whether a person is an **Introvert** or **Extrovert** based on their behavior patterns. The dataset was generated from a deep learning model trained on the *Extrovert vs. Introvert Behavior dataset*.

### Dataset
- **Train set:** 10,189 entries  
- **Test set:** Provided for submission  
- **Target:** `Personality` (binary classification)
- **Features:**
  - `Time_spent_Alone`
  - `Stage_fear`
  - `Social_event_attendance`
  - `Going_outside`
  - `Drained_after_socializing`
  - `Friends_circle_size`
  - `Post_frequency`

---

## 🚀 Models Used

I experimented with multiple classifiers and tuned them to achieve good performance:

| Model                       | Accuracy | Precision | Recall |
|-----------------------------|----------|-----------|--------|
| Support Vector Classifier (SVC) | **0.9603** | **0.8930** | **0.8639** |
| Gradient Boosting Classifier | 0.9588   | 0.8872    | 0.8609 |
| Decision Tree Classifier     | 0.9583   | 0.8845    | 0.8609 |

- SVC performed the best overall.
- Additional preprocessing included encoding categorical variables and scaling features.

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations were created to understand:
- Distribution of personalities
- Social event attendance vs personality
- Stage fear and drained feelings by personality
- Correlation heatmap

---

## 🏆 Results

- **Final Leaderboard Position:** `3855 / 4329`
- **Evaluation Metric:** Accuracy
- This project served as a hands-on experience for:
  - Binary classification
  - Model comparison
  - Feature visualization
  - Confusion matrix interpretation

---


## 📜 Citation

Walter Reade and Elizabeth Park. *Predict the Introverts from the Extroverts.*  
[https://kaggle.com/competitions/playground-series-s5e7](https://kaggle.com/competitions/playground-series-s5e7), 2025. Kaggle.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📌 Future Improvements

- Hyperparameter optimization with GridSearchCV/RandomizedSearchCV
- Ensemble stacking for boosting accuracy
- Using the original dataset alongside generated data for better generalization

---

## ⭐ Acknowledgments

Thanks to Kaggle and the competition hosts for providing this dataset and opportunity to practice and learn.

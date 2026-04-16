# 🎧 Spotify Genre Classification System

## 📌 Overview

This project focuses on building a machine learning model to predict the genre of a music track based on its audio features. The dataset contains multiple attributes such as tempo, energy, loudness, and more, with **114 unique genres**, making it a challenging multi-class classification problem.

---

## 🎯 Objective

To develop a high-performance classification model that accurately predicts the `track_genre` using structured audio data.

---

## 📊 Dataset

* **train.csv** → Used for training the model
* **test.csv** → Used for generating predictions
* Features include:

  * Danceability
  * Energy
  * Loudness
  * Tempo
  * Acousticness
  * And more...

---

## ⚙️ Approach

### 1. Data Preprocessing

* Removed irrelevant columns (`track_id`, `artists`, etc.)
* Encoded categorical features
* Handled mixed data types

### 2. Feature Engineering

* Selected meaningful audio features
* Removed low-importance features

### 3. Model Building

* RandomForest Classifier (baseline)
* XGBoost Classifier (optimized)

### 4. Model Comparison

* Compared models using validation accuracy
* Visualized performance

### 5. Evaluation

* Accuracy Score
* Cross-validation for robustness

---

## 🚀 Results

* Achieved strong performance on validation data
* XGBoost outperformed baseline models
* Built a scalable and efficient pipeline

---

## 📈 Key Learnings

* Handling multi-class classification (100+ classes)
* Importance of feature selection
* Model comparison strategies
* Real-world competition workflow

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib

---

## 📂 Project Structure

```
├── main.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
```

---

## 📌 Future Improvements

* Hyperparameter tuning
* Ensemble models
* Advanced feature engineering

---

## 🏁 Conclusion

This project demonstrates a complete end-to-end machine learning pipeline for solving a complex multi-class classification problem and simulates a real-world data science competition workflow.

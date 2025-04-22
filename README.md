# 🛍️ Customer Behavior Prediction

This project aims to classify customers as **bargain hunters** or **premium buyers** based on their purchase behavior. By understanding customer segmentation, businesses can better tailor their marketing strategies and service offerings.

---

## 📌 Problem Statement

The goal is to predict whether a customer is a bargain hunter or a premium buyer using features like:
- Total amount spent
- Average purchase value
- Number of visits per month

The model uses machine learning (Random Forest Classifier) to analyze this data and classify users accordingly.

---

## 🎯 Objectives

- Preprocess customer purchase history for model training.
- Train a **Random Forest Classifier** on key behavioral features.
- Evaluate model performance using:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix Heatmap
- Visualize insights to interpret the model performance.

---

## 🧠 Methodology

### 🔹 1. Data Preprocessing
- Label encoding for categorical target variable (`buyer_type`)
- Feature selection:
  - `total_spent`
  - `avg_purchase_value`
  - `visits_per_month`
- Train-test split (80/20)

### 🔹 2. Model Training
- Model: **Random Forest Classifier**
- Parameters: `n_estimators=100`, `random_state=42`

### 🔹 3. Evaluation Metrics
- **Accuracy**: Correct predictions over total samples
- **Precision**: Correct premium buyer predictions out of all predicted as premium
- **Recall**: Correct premium predictions out of actual premium buyers
- **Confusion Matrix**: Heatmap for visual interpretation of performance

---

## 📊 Results

- The model performed well, distinguishing between the two customer types effectively.
- Evaluation metrics showed a good balance of precision and recall.
- The confusion matrix highlighted model strengths and errors in classification.

---

## 💡 Technologies Used

- **Python**
- **Pandas** – data handling
- **scikit-learn** – machine learning
- **Seaborn & Matplotlib** – visualization

---

## 📁 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git

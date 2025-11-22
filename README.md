# machine-risk-predictor

# ⚙️ Machine Risk Predictor

A Machine Learning–powered dashboard that predicts **risk levels** using multiple ML classification models — providing analytics, visualizations, and real-time predictions.

This tool helps users understand how machine-condition data translates into potential risk, enabling smarter decision-making and preventive actions.

---

## 🔗 Live App  
👉 **[Open Machine Risk Predictor](https://machine-risk-predictor.streamlit.app/)**

---

## 🧠 Models Used

The system compares performance across 4 powerful ML algorithms:

- **Multi-Layer Perceptron (MLP Classifier)**
- **Gradient Boosting Classifier**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**

Each model is trained, evaluated, and visualized to help users identify the most effective one.

---

## 🚀 Features

- **Model Training & Comparison**  
  Accuracy, precision, recall, F1-score, confusion matrix.

- **Risk Prediction Form**  
  Enter feature values to get predicted machine risk.

- **Interactive Visualizations**  
  ROC curves, confusion matrices, feature importance, and decision insights.

- **Clean & Responsive Dashboard UI**  
  Designed for clarity and ease of use.

---

## 🔧 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py

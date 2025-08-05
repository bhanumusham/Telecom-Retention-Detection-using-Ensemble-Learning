# Telecom-Retention-Detection-using-Ensemble-Learning
A machine learning model built to predict whether a customer is likely to churn based on usage and service data by  leveraging ensemble machine learning models like Random Forest and XGBoost. It includes EDA, data preprocessing,  model evaluation, and deployment through a flask web interface for real-time churn prediction and visualization. 
Here’s a comprehensive and polished `README.md` file you can use to post the **"Telecom Retention Detection Using Ensemble Learning"** project on GitHub:

---

# 📞 Telecom Retention Detection Using Ensemble Learning

## 📌 Project Overview

**Telecom Retention Detection Using Ensemble Learning** is a machine learning-based system designed to identify customers who are at risk of leaving their telecom service providers. The model empowers companies to proactively address churn through predictive analytics, utilizing customer usage patterns, billing behavior, demographics, and service quality.

This project implements an **ensemble learning model** using **VotingClassifier**, combining **Random Forest** and **Decision Tree** classifiers. With an accuracy of **93.19%**, the system provides robust predictions that can be integrated into telecom CRM systems.

---

## 🚀 Features

* Predicts customer churn using historical data
* Utilizes ensemble learning (Random Forest + Decision Tree)
* Provides interpretable feature importance
* Built-in data preprocessing and transformation
* Interactive web-based UI using Flask
* Real-time predictions and analytics
* Supports model retraining and feedback integration

---

## 📊 Dataset

* **Source**: Kaggle - "Telco Customer Churn"
* **Records**: 7043
* **Features**: Customer demographics, billing details, service usage, and more
* **Target**: `Churn` (Yes/No)

---

## 🧠 Machine Learning Models Used

* **Random Forest Classifier**
* **Decision Tree Classifier**
* **VotingClassifier** (Hard voting for ensemble learning)
* Model evaluation metrics:

  * Accuracy: 93.19%
  * Precision, Recall, F1-Score
  * ROC-AUC

---

## 🖥️ System Architecture

```plaintext
Frontend (User Input via Flask UI)
        ↓
Backend (Preprocessing + Feature Engineering)
        ↓
Trained Ensemble Model (RF + DT via VotingClassifier)
        ↓
Output (Prediction + Visualizations)
```

---

## ⚙️ Tech Stack

| Component     | Technology                                              |
| ------------- | ------------------------------------------------------- |
| Language      | Python (≥3.6)                                           |
| Libraries     | pandas, numpy, scikit-learn, matplotlib, seaborn, flask |
| IDE           | Jupyter Notebook, Spyder                                |
| Framework     | Flask                                                   |
| ML Techniques | Ensemble Learning, VotingClassifier                     |
| Deployment    | Localhost (Flask App)                                   |
| Visualization | matplotlib, seaborn                                     |

---

## 📂 Project Structure

```bash
telecom-churn-detection/
│
├── data/                   # Dataset files
├── models/                 # Pickled trained models
├── static/                 # CSS, JS, Images (Flask assets)
├── templates/              # HTML files (Flask templates)
├── app.py                  # Flask backend application
├── churn_predictor.ipynb   # Core machine learning pipeline
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## 🔧 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/telecom-churn-detection.git
   cd telecom-churn-detection
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask application:

   ```bash
   python app.py
   ```

5. Open your browser and visit: `http://localhost:5000`

---

## 📈 Future Enhancements

* Integrate Explainable AI tools like SHAP and LIME
* Real-time data pipelines with Kafka
* Incorporate social media sentiment and network logs
* Deploy via Docker or cloud platforms (e.g., AWS, Heroku)

---

## 📜 License

This project is for academic and learning purposes only.

---

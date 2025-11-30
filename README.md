# 📞 Telecom Retention Detection Using Ensemble Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Ensemble%20Model-orange)
![Flask](https://img.shields.io/badge/Framework-Flask-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
Telecom Retention Detection Using Ensemble Learning is a machine learning system that predicts whether a customer is likely to churn based on historical usage and service data.  
The goal is to help telecom companies identify high-risk customers early and proactively implement retention strategies.

This project integrates **Random Forest + Decision Tree via a VotingClassifier**, achieving **93.19% accuracy** and improving recall for churn-class customers — a critical metric for business decision-making.

---

## 🚀 Key Features
✔ Customer churn prediction using ensemble ML models  
✔ Smart feature engineering and preprocessing pipeline  
✔ Real-time prediction web interface using Flask  
✔ Graphical customer insights and churn analytics  
✔ Model interpretability via feature importance  
✔ Retraining support for scalable deployments

---

## 📊 Dataset
| Attribute | Details |
|---------|---------|
| Source | Kaggle – *Telco Customer Churn* |
| Records | 7,043 customers |
| Target | Churn (Yes / No) |
| Inputs | Demographics, billing, services, usage patterns |

---

## 🧠 Machine Learning Pipeline
| Stage | Description |
|------|-------------|
| EDA | Outlier detection, correlation analysis |
| Preprocessing | Label encoding, scaling, missing value handling |
| Model Training | Random Forest + Decision Tree |
| Ensemble | Hard VotingClassifier |
| Evaluation | Accuracy, Precision, Recall, F1-Score, ROC-AUC |

📌 **Final Accuracy: 93.19%**

---

## 🧩 Challenges & Solutions
| Challenge | Solution |
|----------|----------|
| Imbalanced churn class | SMOTE + stratified train-test split |
| High variance of decision tree | Stabilized with ensemble VotingClassifier |
| Noisy / redundant features | Feature selection via correlation matrix |
| Deployment latency | Optimized preprocessing and model serialization |

---

## ⚡ Business Impact
This system can reduce revenue loss by helping telecom CRM teams identify churn-risk customers before they leave and run targeted campaigns such as discounts, proactive support, and personalized offers.

---

## 🖥️ System Architecture

<img src="https://github.com/bhanumusham/Telecom-Retention-Detection-using-Ensemble-Learning/blob/main/architecture%20diagram.png" alt="Architecture Diagram" width="500" height="500">

---

## 🖥️ Tech Stack
| Component | Technology |
|----------|------------|
| Language | Python |
| ML Libraries | scikit-learn, pandas, numpy |
| Visualization | matplotlib, seaborn |
| Web Framework | Flask |
| Environment | Jupyter Notebook / Spyder |
| Deployment | Localhost – Flask Web App |

---

## 📂 Project Structure

Telecom-Retention-Detection-using-Ensemble-Learning/
│  
├── data/                       # Dataset files (CSV)  
├── models/                     # Serialized trained model (.pkl)  
├── static/                     # CSS, JS, images for Flask UI  
├── templates/                  # HTML templates for Flask frontend  
│  
├── app.py                      # Flask backend / prediction API  
├── churn_predictor.ipynb       # ML pipeline (EDA → Training → Evaluation)  
├── requirements.txt            # Dependencies for environment setup  
└── README.md                   # Project documentation  

---

## 🛠️ Installation & Usage

# Clone the repository
git clone https://github.com/bhanumusham/Telecom-Retention-Detection-using-Ensemble-Learning.git

cd Telecom-Retention-Detection-using-Ensemble-Learning

# Create a virtual environment
python -m venv venv
source venv/bin/activate          # Linux / Mac
venv\Scripts\activate             # Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py

---

## 📈 Results Summary

| Metric               | Value                                                    |
| -------------------- | -------------------------------------------------------- |
| Accuracy             | **93.19%**                                               |
| Precision            | High                                                     |
| Recall (Churn Class) | Improved significantly using ensemble                    |
| Visualizations       | Feature importance, churn distribution, billing patterns |
---

## 🎯 Future Enhancements

Explainable AI (SHAP + LIME)

Real-time streaming data (Kafka integration)

Deploy with Docker / AWS / Render

Multi-language dashboard

SMS/email-based retention recommendation module

---

## 🤝 Contributing

Pull requests are welcome.
If you'd like major changes, please open an issue first to discuss.

---

## ⭐ Support

If you like this repository, please star ⭐ it on GitHub — it helps a lot!

---

## 🧾 License

This project is intended for academic and learning purposes only.

---

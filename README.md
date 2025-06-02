# 🩺 Healthcare Fraud Detection

This project applies machine learning techniques to detect potential fraud in Medicare claims. It combines inpatient, outpatient, and beneficiary datasets to build predictive models capable of identifying fraudulent providers.

---

## 📁 Project Structure

- `Healthcare_Fraud_Detection_Cleaned.ipynb`: Main Jupyter Notebook with full pipeline
- `preprocess.py`: Preprocessing script used in both training and deployment
- `Healthcare_fraud_detection_copy.pkl`: Trained model saved using joblib
- `streamlit_app.py` (optional): Web app interface to run predictions via Streamlit
- `requirements.txt`: List of Python dependencies to run the project

---

## 🚀 How to Run This Project

1. Clone this repository:
```bash
git clone https://github.com/AkhilVijayan0/Projects_Final.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook Healthcare_Fraud_Detection_Cleaned.ipynb
```

4. Run the web app:
```on 
https://healthcare-fraud-detection.streamlit.app/
```

---

## 🧠 Machine Learning Workflow

- Data Loading and Merging
- Exploratory Data Analysis (EDA)
- Feature Engineering (e.g., Claim Duration, Patient Age)
- Data Cleaning & Handling Missing Values
- Model Training (XGBoost, Random Forest, etc.)
- Evaluation using Accuracy, Precision, Recall, etc.
- Deployment using Streamlit

---

## 📊 Dataset

This project uses synthetic or CMS-derived datasets:
- Inpatient Data
- Outpatient Data
- Beneficiary Details
- Provider-level Labels


---

## 📦 Requirements

- Python 3.8+
- pandas, numpy
- scikit-learn
- xgboost
- matplotlib / seaborn
- joblib
- streamlit (for app)

---




---

## 🔮 Future Enhancements

Here are a few directions in which this project can be further improved:

1. **Model Optimization**  
   - Perform hyperparameter tuning using GridSearchCV or Optuna.
   - Try advanced models like LightGBM or ensemble stacking.

2. **Explainability**  
   - Integrate SHAP or LIME to explain model predictions and improve trustworthiness.

3. **Real-Time Monitoring**  
   - Deploy the model in a production pipeline with real-time fraud detection capability.

4. **Anomaly Detection Models**  
   - Explore unsupervised methods like Isolation Forest or Autoencoders for detecting new fraud patterns.

5. **Improved UI for Streamlit**  
   - Add visualizations, interactive summaries, and patient-level insights in the Streamlit app.

6. **Data Pipeline Automation**  
   - Automate data ingestion and preprocessing using tools like Apache Airflow or Prefect.

7. **Cloud Deployment**  
   - Deploy the Streamlit app on platforms like Streamlit Cloud, AWS, or Azure with CI/CD integration.


📝 Author Akhil Vijayan Email: akhilvijayan15003@gmail.com LinkedIn: https://www.linkedin.com/in/akhil-vijayan2003/

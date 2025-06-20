
# 🏥 Healthcare Fraud Detection – Streamlit App

This Streamlit web application detects **potential fraudulent healthcare claims** using a machine learning model trained on real-world healthcare data. The app supports both **CSV file uploads** and **manual data entry**, making it easy to analyze either multiple claims or a single one.

---

## 📊 Dataset Source

The model is trained on the **2009 Medicare Claims dataset**, which includes information about beneficiaries, inpatient/outpatient services, physicians, and claim details. The dataset has been preprocessed and engineered to extract meaningful insights for fraud detection.

---

## 🚀 How to Use the App

### 🧩 Step 1: Choose Input Format

You can interact with the app using either:

#### 1️⃣ Upload CSV File
- Upload a `.csv` file with the **same column names** and **correct data types**.
- Predictions will be shown for each row in the uploaded file.

#### 2️⃣ Manual Input
- Use the sidebar form to input data for a **single patient/claim**.
- Useful for testing individual cases.

---

## 📥 Required Input Columns & Formats

| Column Name               | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| **Provider ID**           | Unique provider ID (Format: `"PRV"` + 5 digits, e.g., `PRV51001`)          |
| **Beneficiary ID**        | Unique patient ID (Format: `"BENE"` + 5 digits, e.g., `BENE67890`)         |
| **Date of Birth (DOB)**   | Patient’s date of birth (`YYYY-MM-DD`)                                     |
| **Claim Start Date**      | Date when the claim starts (`YYYY-MM-DD`)                                  |
| **Claim End Date**        | Date when the claim ends (`YYYY-MM-DD`)                                    |
| **Claim Amount (Reimbursed)** | Amount reimbursed by insurance (float/integer)                      |
| **Physician ID**          | ID of the consulting physician                                              |
| **Admission Date**        | Hospital admission date (`YYYY-MM-DD`) or `0` if not admitted              |
| **Discharge Date**        | Date of discharge (`YYYY-MM-DD`) or `0` if not discharged                  |
| **Deductible Amount Paid**| Amount paid by patient at hospital (integer/float)                         |
| **ClmDiagnosisCode_1**    | Diagnosis code from medical record (alphanumeric)                          |
| **Gender**                | Gender: `1` = Male, `2` = Female                                            |
| **Race**                  | Patient’s race: `1`: White, `2`: Black, `3`: Asian, `4`: Other             |
| **Renal Disease Indicator** | Indicates End-Stage Renal Disease: `1`: Yes, `0`: No                    |
| **State**                 | Patient's residence state:  
                              `1`: California  
                              `2`: Texas  
                              `3`: Florida  
                              `4`: New York  
                              `5`: Pennsylvania  
                              `6`: Illinois  
                              `7`: Ohio                            |
| **Country Number**        | Country number/code the patient belongs to (integer)                       |
| **Diseases**              | Select or list the diseases the patient has                                 |

---

## 🎯 Output

After processing, the app provides:
- A prediction for each entry: ✅ **Not Fraud** or ❌ **Potential Fraud**
- Visualizations like fraud ratios (if multiple entries are provided)
- CSV-based predictions are shown in tabular format with predictions appended

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Streamlit**
- **Pandas / NumPy**
- **Scikit-learn / XGBoost**

---

## 📂 Sample Files

📄 `sample_input.csv` is included in the repository to demonstrate the expected structure and format.
📄 Sample Datasets are  included in the repository (Sample Data Folder) to demonstrate the expected structure and format.


---

## 🌐 Live App

🔗 **Check out the live app here**:  
👉 [https://healthcare-fraud-detection.streamlit.app/](https://healthcare-fraud-detection.streamlit.app/)

---

## 🔗 Connect with Me

📇 [Akhil Vijayan on LinkedIn](https://www.linkedin.com/in/akhil-vijayan2003)

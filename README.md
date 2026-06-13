#  EHR Patient Readmission Prediction Model

> Predicting 30-day hospital readmission risk from electronic health records using machine learning.

---

##  Overview

Hospital readmissions within 30 days are a major driver of healthcare costs and a key indicator of care quality. This project builds a machine learning model using Electronic Health Record (EHR) data to predict which patients are at high risk of readmission — enabling earlier intervention and better resource allocation.

**Model accuracy: 80%**

---

##  Quickstart

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/ehr-readmission-model.git
cd ehr-readmission-model

# Install dependencies
pip install -r requirements.txt

# Run the model
python run.py
```

---

##  Results

| Metric | Score |
|---|---|
| Accuracy | 80% |
| Precision | TBD |
| Recall | TBD |
| AUC-ROC | TBD |

---

##  Data

- **Source:** Electronic Health Records (EHR)
- **Features used:** Patient demographics, diagnosis codes, medications, length of stay, prior admissions, lab values
- **Target variable:** 30-day readmission (binary: Yes / No)
- **Preprocessing:** Missing value imputation, feature encoding, normalization

---

##  Methods

- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- Model training and evaluation (Logistic Regression, Random Forest, XGBoost)
- Cross-validation and hyperparameter tuning

---

##  Project Structure

```
ehr-readmission-model/
├── data/               # Raw and processed data
├── notebooks/          # Jupyter notebooks for EDA
├── src/                # Source code
│   ├── preprocess.py
│   ├── train.py
│   └── evaluate.py
├── requirements.txt
└── run.py
```

---

##  Author

**Amina Khatun**  
Graduate Student | Public Health & Data Science  
 Saint Louis, Missouri  
[www.linkedin.com/in/amina-khatun-25b516340)

---

##  Citation

If you use this work, please cite:
```
Khatun, A. (2025). EHR Patient Readmission Prediction Model. GitHub.
https://github.com/YOUR_USERNAME/ehr-readmission-model
```

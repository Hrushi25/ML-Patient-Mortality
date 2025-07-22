# ML-Patient-Mortality
# 🧠 Predicting Patient Mortality using Machine Learning

This project focuses on predicting **patient mortality risk** using anonymized COVID-19 medical data. We explored traditional machine learning models and neural networks to classify whether a patient would **live or die**, based on various health indicators like age, comorbidities, hospitalization, and COVID-positive status.

---

## 📁 Project Structure

predicting-patient-mortality/
├── Project_Predicting_Patient_Mortality.ipynb # Main notebook
├── figures/ # Visualizations (SHAP, metrics, etc.)
├── data/ # Sample dataset & data readme
├── requirements.txt # Python dependencies
└── README.md # Project overview (this file)



---

## 📊 Dataset

- Anonymized dataset with **1,048,576 patient records**.
- Features include:
  - Demographics: `AGE`, `SEX`
  - Health conditions: `DIABETES`, `HYPERTENSION`, `OBESITY`, etc.
  - COVID-specific info: `COVID_POSITIVE`, `HOSPITALIZED`, `PNEUMONIA`
- **Target variable**: `DEATH` (1 = Died, 0 = Lived)

---

## 🤖 Models Used

- Decision Tree
- Random Forest
- Gradient Boosting (LightGBM)
- Neural Network (Keras)

---

## 📈 Evaluation Metrics

- Accuracy
- Precision, Recall
- F1 Score
- ROC-AUC
- SHAP values for interpretability

---

## 📊 Visualizations

- Disease prevalence across age groups
- Feature correlation heatmap
- Decision tree visualization
- Hyperparameter heatmap for Random Forest
- SHAP summary & importance plots
- F1 score comparison
- Training/Validation metrics (NN)
- Threshold vs Metrics plot

(See `figures/` folder)

---

## ⚙️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/predicting-patient-mortality.git
cd predicting-patient-mortality

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Project_Predicting_Patient_Mortality.ipynb

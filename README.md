#📌 Project Overview

This project develops a machine learning model using XGBoost to predict viral load (VL) suppression status among people living with HIV (PLHIV). The goal is to support early identification of patients at risk of virologic failure, enabling targeted clinical and programmatic interventions.

The model leverages routinely collected clinical, behavioral, and treatment-related variables commonly available in HIV programs in low- and middle-income settings.

🎯 Objectives

Predict whether a patient is virally suppressed or unsuppressed

Identify key drivers of virologic non-suppression

Support data-driven clinical decision-making

Demonstrate the use of advanced ML (XGBoost) in public health analytics

🧠 Features Used

The model uses a mix of clinical, behavioral, and treatment adherence indicators, including:

ART adherence level

Pill stock-out history

Drug regimen type

Pill burden (NCD co-medications)

Smoking status

Alcohol use

History of treatment denial or interruption

WHO clinical stage

Presence of opportunistic infections (OIs)

📌 Note: Synthetic data were generated to preserve privacy while maintaining realistic clinical patterns.

🗂 Dataset

Type: Synthetic HIV clinical dataset

Size: ~15,000 patient records

Target Variable: Viral Load Suppression (0 = Unsuppressed, 1 = Suppressed)

Class Balance: Minority class intentionally increased to ≥30% to address imbalance

📌 Placeholder:
[INSERT DATA DICTIONARY TABLE HERE]

⚙️ Methodology

Data preprocessing and encoding

Train–test split

Handling class imbalance

Model training using XGBoost Classifier

Hyperparameter tuning

Model evaluation using multiple performance metrics

📊 Model Performance

The model was evaluated using:

Accuracy

Precision

Recall

F1-score

ROC–AUC

Cross-validated ROC–AUC

📌 Key Results (example – update as needed):

ROC–AUC: [INSERT VALUE]

CV ROC–AUC: [INSERT VALUE]

Recall (Unsuppressed class): [INSERT VALUE]

📌 Placeholder:
[INSERT CONFUSION MATRIX FIGURE HERE]

📌 Placeholder:
[INSERT ROC CURVE FIGURE HERE]

🔍 Feature Importance

XGBoost feature importance analysis highlights variables most associated with virologic outcomes.

📌 Placeholder:
[INSERT FEATURE IMPORTANCE PLOT HERE]

Key insights include:

Adherence-related factors strongly influence suppression

Treatment interruptions and pill burden increase risk of failure

Behavioral factors contribute meaningfully to prediction

🏥 Public Health & Clinical Use Cases

Early warning system for patients at risk of virologic failure

Prioritization tool for enhanced adherence counseling (EAC)

Resource optimization in high-burden HIV programs

Program monitoring and quality improvement

⚠️ Limitations

Synthetic data may not capture all real-world complexities

Model performance may vary across settings

Does not replace clinical judgment

External validation is required before deployment

🚀 Future Work

Validate model on real-world VL datasets

Integrate into DHIS2 / EMR systems

Develop real-time dashboards (Power BI / Streamlit)

Add time-series VL prediction

Incorporate explainability tools (SHAP)

🛠 Tech Stack

Python

XGBoost

Scikit-learn

Pandas, NumPy

Matplotlib / Seaborn

📁 Repository Structure
├── data/
├── notebooks/
│   └── VL_predictor_using_XGBoost.ipynb
├── figures/
├── README.md
└── requirements.txt
👤 Author

Andy Okebugwu, PhD
Public Health Physician | Data Scientist

📌 Placeholder:

LinkedIn: [INSERT LINK]

Portfolio: [INSERT LINK]

Email: [INSERT EMAIL]

📌 Project Overview
This project performs a complete Exploratory Data Analysis (EDA) on the Healthcare Stroke Dataset from Kaggle. The goal is to identify key 
risk factors that contribute to stroke occurrence using data analysis and visualization techniques.





📊 Dataset Information

FeatureDetailSourceKaggle - Stroke Prediction DatasetRows5,110Columns12



Key Columns:


ColumnDescriptionagePatient agehypertensionHigh blood pressure (0/1)heart_diseaseHeart disease (0/1)avg_glucose_levelAverage blood 

glucosebmiBody Mass Indexsmoking_statusSmoking habitstrokeTarget — Stroke occurred (0/1)


🧹 Data Cleaning

✅ Checked and removed duplicate records — 0 duplicates found

✅ BMI had 201 missing values — filled with mean value
✅ All other columns had 0 missing values
✅ Dataset ready for analysis after cleaning




📈 Visual Analysis

1️⃣ Age Distribution


Most patients are between 40–70 years old

Very few patients are below 20 or above 80


2️⃣ Stroke Count
StrokeCountNo Stroke (0)4,861Stroke (1)249



Dataset is highly imbalanced — only ~5% patients had stroke



3️⃣ Gender Distribution
GenderCountFemale2,994 (58.6%)Male2,115 (41.4%)Other1
4️⃣ Age vs Stroke

Average AgeNo Stroke41.97 yearsStroke67.73 years

➡️ Stroke patients are significantly older

5️⃣ Glucose Level vs Stroke

Avg GlucoseNo Stroke104.79 mg/dLStroke132.54 mg/dL
➡️ Higher glucose = higher stroke risk

6️⃣ BMI vs Stroke

Avg BMINo Stroke28.82Stroke30.21

➡️ Slight increase in BMI in stroke patients


💡 Key Insights
FindingDetail🔴 AgeStrongest indicator — stroke risk increases heavily after 60🔴 Glucose LevelHigh glucose strongly linked to stroke🟡 BMIModerate relationship with stroke🟡 SmokingSmokers and formerly smoked have higher risk🟢 GenderVery little impact on stroke occurrence

✅ Conclusion

Age and Glucose Level are the strongest predictors of stroke.
Patients above 60 years with high glucose levels should be monitored closely.


Gender alone is not a significant factor in stroke prediction.





🛠️ Tech Stack

ToolPurposePythonCore programmingPandasData manipulationNumPyNumerical operationsMatplotlibData visualizationGoogle ColabDevelopment 
environment


📂 Project Structure

Stroke-Analysis/

├── stroke_analysis.ipynb    # Main analysis notebook

├── healthcare-dataset-stroke-data.csv  # Dataset

└── README.md                # Project documentation



🚀 How to Run

bash# Clone the repo

git clone https://github.com/samichohan/Data-Analysis-Projects.git


# Open notebook
jupyter notebook stroke_analysis.ipynb

Or open directly in Google Colab.



👤 Author

Sami Chohan







# Heart Failure Prediction

Cardiovascular diseases (CVDs) are the leading cause of death globally, accounting for an estimated 17.9 million deaths per year, about 31% of all deaths worldwide. Heart failure is a common consequence of CVD, and this project uses a clinical dataset with 12 features to predict mortality from heart failure.

Most CVDs are preventable by addressing behavioural risk factors such as tobacco use, poor diet, obesity, physical inactivity, and harmful alcohol use. For people already at high cardiovascular risk (due to hypertension, diabetes, hyperlipidaemia, or existing disease), early detection matters, and a machine learning model can help.

## Background

Heart failure occurs when the heart muscle weakens and enlarges, limiting its ability to pump blood, or when the ventricles stiffen and no longer fill properly between beats. Over time the heart can't meet the body's demand for blood, and patients begin experiencing symptoms such as breathlessness.

Common causes include coronary heart disease, diabetes, high blood pressure, and other conditions such as HIV, substance abuse, thyroid disorders, excess vitamin E, and radiation or chemotherapy. Per the WHO, coronary heart disease now accounts for 31% of deaths globally, and its prevalence is rising in India in particular, where dietary and risk-factor patterns differ from other countries.

The goal of this project is to estimate mortality risk from heart failure and examine its relationship with major risk factors.

## Dataset

13 columns, with the first 12 used as independent variables and `DEATH_EVENT` as the binary target:

| Feature | Type |
|---|---|
| Age | Float, discrete |
| Anaemia | Binary |
| Creatinine phosphokinase | Continuous |
| Diabetes | Binary |
| Ejection fraction | Discrete |
| High blood pressure | Binary |
| Platelets | Float, discrete |
| Serum creatinine | Continuous |
| Serum sodium | Discrete |
| Sex | Binary |
| Smoking | Binary |
| Time | Discrete |
| **DEATH_EVENT (target)** | Binary |

Since `DEATH_EVENT` is binary, this is a binary classification problem.

## Repository contents

| File | Description |
|---|---|
| `Heart Failure Prediction.ipynb` | Full analysis: EDA, preprocessing, and model comparison |
| `heart_failure_dataset.csv` | Source dataset |
| `Description, Approach, Result Interpretation and Conclusion.pdf` | Write-up of approach, results, and conclusions |

## Approach

Multiple classification models are trained and compared to predict heart failure mortality as accurately as possible. See the notebook for the full modeling workflow, and the PDF for the detailed results, interpretation, and conclusion.

## Tools

Python · pandas · NumPy · scikit-learn · matplotlib / seaborn · Jupyter Notebook

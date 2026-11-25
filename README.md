# Weather-Based Road Accident Risk Prediction Using Machine Learning and Explainable AI

## About the Project

This project is based on predicting road accident risk using different weather conditions. The aim is to study how factors such as temperature, humidity, pressure, visibility, wind speed and precipitation can be used for accident risk classification.

The project uses Machine Learning algorithms to classify accident risk into three categories: Low, Medium and High.

## Dataset

The dataset contains 12,000 US accident records from April to September 2022.

The input features used are:
- Temperature
- Humidity
- Pressure
- Visibility
- Wind Speed
- Precipitation
- Weather Condition

The target variable is divided into three classes:
- Low – Severity 1
- Medium – Severity 2
- High – Severity 3 and 4

## Models Used

The following Machine Learning algorithms were implemented:

1. Logistic Regression
2. Random Forest
3. XGBoost

The performance of these models was compared using different evaluation metrics.

## Results

The Random Forest model achieved the following results:

| Metric | Score |
|---|---:|
| Accuracy | 69.38% |
| Precision | 65.33% |
| Recall | 69.38% |
| Weighted F1-Score | 65.80% |
| Macro F1-Score | 62.91% |

## Explainable AI

SHAP was used to understand the model predictions and identify which weather features contributed most to the predictions.

The important features identified were:
- Pressure
- Humidity
- Weather Condition
- Temperature
- Wind Speed

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP

## How to Run

1. Download or clone this repository.
2. Open the notebook in Google Colab.
3. Upload the required dataset.
4. Run the notebook cells one by one.

## Research Publication

**Journal:** International Journal of Advanced Research in Science, Communication and Technology (IJARSCT)

**Volume:** 6, Issue 3

**Publication:** September 2026

## Author

Vaishnavi Raju Chavan

MCA Student

Research Guide: Ms. Yogita Kadbane

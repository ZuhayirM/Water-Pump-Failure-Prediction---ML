# Water-Pump-Failure-Prediction---ML

## Project Overview
This project uses machine learning to predict whether a water pump is functional or non-functional. The goal is to support better maintenance planning by identifying pumps that are likely to fail.

## Objective
- Build classification models to predict water pump functionality
- Compare multiple machine learning algorithms
- Select the best-performing model using validation metrics

## Dataset
The dataset includes information about water pumps such as:
- GPS height
- Latitude and longitude
- Population served
- Water source type
- Water quality
- Installation year
- Pump type
- Functioning status

After data preprocessing, the dataset contained 4,518 observations and 14 features.

## Models Used
- Naïve Bayes
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest / Ensemble Methods
- Neural Network
- Naïve baseline model

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Specificity
- AUC-ROC

## Model Performance

| Model | Accuracy |
|------|------|
| Naïve Baseline | 59.22% |
| KNN | 70.35% |
| Naïve Bayes | 72.42% |
| Logistic Regression | Evaluated in project report |
| Random Forest / Ensemble | Evaluated in project report |
| Neural Network | Evaluated in project report |

Naïve Bayes achieved the best validation accuracy in this project.

## Business Impact
This project can help organizations:
- Detect likely pump failures earlier
- Reduce repair costs
- Improve maintenance planning
- Reduce downtime in water supply systems

## Tools and Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Files in This Repository
- `water_pump_prediction.ipynb` – main notebook with preprocessing, modeling, and evaluation
- `final_report.pdf` – final project report
- `model_results.html` – HTML export of notebook/results

## Author
Zuhayir Mustafa  
MS in Business Analytics  
University of North Texas

# Cricket Match Win Prediction

## Project Overview

This project was completed as an academic capstone project as part of my Data Science and Business Analytics programme.

The study explores the use of historical international cricket match data involving the Indian cricket team to identify patterns associated with match outcomes and develop machine learning classification models to predict win/loss results.

The project focuses on exploratory data analysis, data preprocessing, clustering, model development, and performance evaluation.

## Project Objective

To analyse historical cricket match data, identify factors associated with match outcomes, and compare machine learning classification algorithms to determine the best-performing model within the scope of this academic study.

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. **Data Loading and Exploration** – Loaded the historical cricket dataset and examined its structure, variables, and data quality.
2. **Data Cleaning and Preprocessing** – Analysed missing values, handled data quality issues, and prepared the dataset for analysis.
3. **Exploratory Data Analysis (EDA)** – Performed univariate, bivariate, and multivariate analysis to explore patterns and relationships in the data.
4. **Clustering Analysis** – Applied K-Means clustering to explore patterns and groupings in the dataset.
5. **Model Development** – Developed and compared four classification algorithms:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
6. **Model Evaluation** – Compared model performance using Accuracy, Precision, Recall, F1-score, and ROC-AUC. GridSearchCV was also used for hyperparameter tuning in selected models.

## Model Performance

According to the submitted academic project report, Gradient Boosting achieved the strongest overall performance among the four evaluated classification models.

| Evaluation Metric | Reported Result |
|---|---:|
| Test Accuracy | 95.10% |
| Weighted Precision | 95% |
| Weighted Recall | 95% |
| Weighted F1-score | 95% |
| ROC-AUC | 96.86% |

These figures are reproduced from the original academic report and have not been independently revalidated for this GitHub publication.

## Key Limitations

This project is an academic exercise and has limitations that should be considered when interpreting its results.

- The analysis relies on historical match data.
- Real-time factors such as player injuries, weather conditions, pitch reports, and player fitness were not included.
- Historical patterns may not fully represent changes in team strategies or player performance.
- Match outcomes can be influenced by unpredictable events that are difficult to capture in structured datasets.

The results should therefore be interpreted within the scope of the original academic study rather than as evidence of production-ready predictive performance.

## Repository Contents

| File | Description |
|---|---|
| `Cricket_Match_Win_Prediction.ipynb` | Original Python notebook containing the analysis and modelling workflow |
| `Capstone_Project_Final_Report.pdf` | Final academic project report |

## Dataset Availability

The original dataset is not included in this repository.

The notebook references a local Excel workbook named `Sports Data.xlsx` and the worksheet `Sports data for DSBA`. The workbook must be obtained separately and made available at the file path expected by the notebook to execute the data-loading steps.

## Learning and Further Development

This capstone project provided practical exposure to exploratory data analysis, data preprocessing, clustering, classification algorithms, and model evaluation.

Feedback received during the academic evaluation also highlighted areas for further improvement. I am continuing to strengthen my understanding of machine learning concepts, preprocessing practices, model validation, and predictive modelling through further learning and practice.

---

**Project Type:** Academic Capstone Project  
**Domain:** Sports Analytics  
**Focus:** Cricket Match Outcome Classification

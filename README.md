
# Early-Stage-Diabetes-Prediction

A predictive modeling project using the Early Stage Diabetes Risk Prediction dataset. This repository contains code and documentation for analyzing clinical and demographic data to identify key risk factors associated with early-stage diabetes and develop predictive models.

---

## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Methodology](#methodology)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Limitations](#limitations)
- [How to Use](#how-to-use)
- [Acknowledgements](#acknowledgements)

---

## Introduction
This project leverages the Early Stage Diabetes Risk Prediction dataset from the UCI Machine Learning Repository. It aims to identify significant predictors of diabetes risk and build robust predictive models using various machine learning techniques.

The project is divided into two phases:
1. **Phase 1:** Data preparation, exploratory analysis, and feature selection.
2. **Phase 2:** Model building, evaluation, and comparison of classifiers.

---

## Dataset Overview
- **Source:** UCI Machine Learning Repository
- **Size:** 521 records
- **Features:** Clinical and demographic attributes, including:
  - Polyuria
  - Polydipsia
  - Sudden weight loss
  - Partial paresis
  - Age, Gender, and more.

The target variable indicates the presence or absence of early-stage diabetes.

---

## Methodology
1. **Data Preparation:**
   - Encoding categorical variables.
   - Min-max scaling for numerical features.
   - Splitting the data into training (70%) and testing (30%) sets.

2. **Feature Selection:**
   - Features were ranked using the F-score method to determine their importance in predicting diabetes risk.

3. **Model Evaluation:**
   - Models were evaluated using the ROC AUC metric.
   - Hyperparameter tuning was performed using GridSearchCV.
   - Statistical tests (Paired t-tests) were conducted to compare model performance.

---

## Models and Techniques
The following machine learning models were implemented:
- K-Nearest Neighbors (KNN)
- Decision Trees (DT)
- Naive Bayes (NB)
- Random Forest (RF)
- Gradient Boosting Classifier (GBC)

The models were fine-tuned for optimal performance and compared based on their predictive accuracy and interpretability.

---

## Results
- **Top Features Identified:** Polyuria, Polydipsia, Sudden weight loss, Partial paresis.
- **Best Model Performance:** Gradient Boosting Classifier achieved the highest ROC AUC score.
- Detailed model comparison results are provided in the analysis.

---

## Limitations
- Small dataset size may limit model generalizability.
- Models may overfit due to a limited number of features.
- Further validation on external datasets is recommended.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/ChamodiMadara/Early-Stage-Diabetes-Prediction.git ```

 2. Install required libraries:
   - **Python**: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`.

3. Open the Jupyter Notebook and run the code:
   - `Diabetes_Data_prediction.ipynb`

---
## Acknowledgements
I would like to express my gratitude to:
- **UCI Machine Learning Repository** for providing the free dataset used in this project.
- **Instructors and Mentors** for their guidance and support throughout this project.
- All resources and documentation that enabled me to learn and implement various machine learning techniques effectively.

This project is a result of my dedication to understanding predictive modeling and exploring its applications in healthcare analytics.


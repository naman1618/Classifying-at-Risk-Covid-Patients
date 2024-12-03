# Classifying At-Risk COVID-19 Patients Using Machine Learning

This project focuses on building a machine learning model to predict the mortality risk of COVID-19 patients. By leveraging supervised learning techniques, the model aims to identify high-risk patients, enabling timely interventions to save lives and optimize healthcare resources.

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Dataset Description](#dataset-description)
- [Approach and Methodology](#approach-and-methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributors](#contributors)
- [License](#license)

---

## **Project Overview**
The COVID-19 pandemic has placed significant strain on healthcare systems worldwide. This project applies machine learning techniques to identify patients at high risk of mortality due to COVID-19. By analyzing patient data, the model can help healthcare providers prioritize resources and design targeted intervention strategies.

---

## **Key Features**
- Comprehensive data cleaning and preprocessing, including handling missing values, standardizing binary variables, and normalizing numerical features.
- Application of multiple supervised learning models: logistic regression, K-nearest neighbors (KNN), Naive Bayes, decision tree, and random forest.
- Comparative model evaluation to identify the best-performing algorithm.
- Visualization of key findings for interpretability and decision-making.

---

## **Dataset Description**
- **Source:** Due to privacy concerns, the dataset details are anonymized. The dataset includes patient demographic, clinical, and laboratory information.
- **Features:**
  - Age, gender, and pre-existing conditions.
  - Vital signs and laboratory test results.
  - Binary outcome variable: `1` for mortality, `0` for survival.
- **Size:** Approximately 5,000 patient records and 20 features.

---

## **Approach and Methodology**
1. **Data Cleaning & Feature Engineering:**
   - Handled missing values through imputation.
   - Standardized binary variables (e.g., gender, pre-existing conditions).
   - Normalized numerical variables (e.g., vital signs, lab results).

2. **Model Selection:**
   - Trained multiple models: logistic regression, KNN, Naive Bayes, decision tree, and random forest.
   - Evaluated models based on accuracy, precision, recall, and F1-score.

3. **Model Evaluation:**
   - Performed hyperparameter tuning to optimize model performance.
   - Chose logistic regression as the final model with an accuracy of **85.50%**.

4. **Visualization:**
   - Used confusion matrices, precision-recall curves, and feature importance charts to interpret results.

---

## **Results**
- **Best Model:** Logistic Regression
- **Accuracy:** 85.50%
- **Insights:**
  - Older age and certain pre-existing conditions were strong predictors of mortality.
  - High-risk patient clusters were identified, providing actionable insights for healthcare providers.

---

## **Technologies Used**
- **Programming Languages:** Python
- **Libraries:** 
  - Data manipulation: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-learn`
- **Tools:**
  - Jupyter Notebook for development and visualization.

---

## **Setup and Installation**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/COVID19-Mortality-Risk.git
   cd COVID19-Mortality-Risk

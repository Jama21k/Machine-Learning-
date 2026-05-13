# Divorce Prediction Using Machine Learning

## Overview

This project investigates the growing global issue of divorce through the application of machine learning techniques. Using the Divorce Predictor Scale (DPS), the study aims to identify key behavioral and relational indicators associated with marital instability and divorce outcomes.

The project applies multiple machine learning algorithms, including Support Vector Machines (SVM), Neural Networks, and Random Forest models, to predict divorce likelihood and evaluate the predictive power of DPS survey features. Additionally, the research identifies the top features most strongly associated with divorce prediction.

---

## Background

Divorce has significant personal, social, and psychological consequences for couples and their families. Research has shown that divorce can negatively impact mental health, financial stability, and long-term well-being, especially among children.

At the same time, successful marriages are associated with improved happiness, health outcomes, and overall life satisfaction. Despite these benefits, divorce rates have increased globally over recent decades, leading researchers to investigate the underlying factors contributing to marital dissolution.

This project explores whether machine learning models can effectively predict divorce outcomes using relationship-based survey indicators from the Divorce Predictor Scale.

---

## Objectives

The primary objectives of this study are:

* Predict divorce outcomes using machine learning algorithms
* Evaluate and compare the performance of different classification models
* Identify the most influential features associated with divorce prediction
* Analyze relationships between DPS indicators and marital stability
* Improve predictive accuracy using advanced computational methods

---

## Machine Learning Models Used

The following models were implemented and evaluated:

* Support Vector Machine (SVM)
* Neural Networks
* Random Forest
* Logistic Regression (optional if included)
* Other classification techniques where applicable

---

## Dataset

The project utilizes the Divorce Predictor Scale (DPS) dataset, which contains survey-based relationship indicators associated with marital outcomes.

### Features Include:

* Communication quality
* Conflict frequency
* Emotional compatibility
* Trust and understanding
* Behavioral interaction patterns
* Relationship satisfaction indicators

### Target Variable:

* Divorce outcome (Divorced / Not Divorced)

---

## Methodology

### Data Preprocessing

* Data cleaning and validation
* Feature scaling and normalization
* Train-test split
* Exploratory data analysis (EDA)

### Model Training

* Hyperparameter tuning
* Cross-validation
* Model optimization

### Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

---

## Key Findings

* Certain DPS indicators demonstrated strong predictive relationships with divorce outcomes.
* Machine learning models achieved high predictive performance in classifying divorce likelihood.
* Features related to communication patterns and emotional disconnect were among the strongest predictors.
* The study identified the top 10 features most correlated with divorce prediction.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Repository Structure

```text
├── data/
├── notebooks/
├── models/
├── visuals/
├── src/
├── README.md
└── requirements.txt
```

---

## Future Improvements

* Expand dataset diversity across cultures and demographics
* Incorporate deep learning architectures
* Deploy model as an interactive web application
* Explore explainable AI techniques for model interpretability

---

## References

* Amato, P. (2000)
* Sun, Y. (2008)
* Be et al. (2013)
* Vanassche et al. (2013)
* Whisman et al. (2018)
* Eurostat (2023)
* Wilkinson & Finkbeiner (2024)
* Ortiz-Ospina et al. (2020)

---

## Author

Hussein Jama

Aspiring Data Analyst and Machine Learning enthusiast focused on predictive modeling, business intelligence, and data-driven research.

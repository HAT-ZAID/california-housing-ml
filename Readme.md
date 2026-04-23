# California Housing Price Prediction

This project is based on the workflow presented in *Hands-On Machine Learning with Scikit-Learn & TensorFlow* by Aurélien Géron. It was developed as a hands-on exercise to understand and implement a complete machine learning pipeline using real-world data.

---

## Overview

The goal is to predict median housing prices in California districts using demographic and geographic features. The focus of this project is not just model performance, but building a clear understanding of the end-to-end process involved in a typical machine learning task.

---

## Workflow

* Data acquisition
* Exploratory data analysis
* Data preprocessing and cleaning
* Feature engineering
* Model training
* Model evaluation

---

## Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

---

## Key Concepts

* Train-test splitting and stratified sampling
* Handling missing values
* Feature scaling and transformation
* Pipelines using scikit-learn
* Cross-validation
* Evaluation using RMSE

---

## Project Structure

```
california-housing-ml/
│
├── notebooks/
│   └── california_housing_price_prediction.ipynb
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## Setup

Clone the repository:

```
git clone https://github.com/HAT-ZAID/california-housing-ml.git
cd california-housing-ml
```

Run the notebook:

```
jupyter notebook
```

---

## Results

Among the models tested, the Random Forest Regressor provided the best performance with lower prediction error compared to simpler models.

---

## Notes

This was a guided tutorial-based project and also a useful exercise to reinforce core machine learning concepts through implementation.

---

## Future Work
* Additional Exercises
* Converting the notebook into modular code
* Model deployment
* Experiment tracking

---

## Reference

*Hands-On Machine Learning with Scikit-Learn & TensorFlow* — Aurélien Géron

# Rock vs Mine Prediction using Machine Learning

## Project Overview

This project is a Machine Learning-based classification system that predicts whether an underwater object is a Rock or a Mine using sonar signal data.

The project uses the Sonar Dataset and applies Machine Learning algorithms to classify objects based on sonar signal patterns.

---

## Dataset Information

The project uses the Sonar Dataset for binary classification.

Each row in the dataset represents sonar signal measurements reflected from underwater objects.

### Target Classes

* `R` → Rock
* `M` → Mine

### Dataset Features

* 60 numerical input features
* 1 output label column

The numerical values represent sonar signal energy at different frequencies.

---

## Technologies Used

* Python
* pandas
* NumPy
* scikit-learn

---

## Machine Learning Algorithm Used

* Logistic Regression

The Logistic Regression model was trained on the sonar dataset to classify whether the detected object is a Rock or a Mine.

---

## Project Workflow

1. Load and preprocess the dataset
2. Split the data into training and testing sets
3. Train the Logistic Regression model
4. Evaluate model accuracy
5. Predict whether the object is Rock or Mine using custom input data

---

## Model Performance

* Training Accuracy: 83.42%
* Testing Accuracy: 76.19%

The model performs reasonably well on unseen data and demonstrates the practical implementation of binary classification using Logistic Regression.

---

## Prediction System

The project also includes a prediction system where random input samples from the dataset can be provided to the trained model to predict whether the object is:

* Rock
* Mine

This demonstrates the inference capability of the trained Machine Learning model.

---

## Libraries Imported

```python id="ojx6k7"
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
```

## Future Improvements

* Experiment with advanced classification models
* Add visualization and exploratory data analysis
* Deploy using Streamlit
* Improve prediction accuracy using feature engineering

---

## Author

Adithyan Anil Kumar

# Diabetes Prediction using Machine Learning

## Problem Statement

The objective of this project is to develop a machine learning model that predicts whether a person is diabetic based on various diagnostic measurements.

The project uses the **PIMA Diabetes Dataset** and treats the problem as a **binary classification** task, where the model predicts either diabetic (`1`) or non-diabetic (`0`).

## Dataset

The dataset contains **768 records** and **8 input features** along with the target variable `Outcome`.

### Features

* **Pregnancies** - Number of times the patient has been pregnant
* **Glucose** - Plasma glucose concentration
* **BloodPressure** - Diastolic blood pressure
* **SkinThickness** - Triceps skin fold thickness
* **Insulin** - 2-hour serum insulin level
* **BMI** - Body Mass Index
* **DiabetesPedigreeFunction** - Diabetes pedigree function
* **Age** - Age of the patient

### Target

**Outcome**

* `0` - Non-diabetic
* `1` - Diabetic

## Solution Approach

The project follows an end-to-end machine learning workflow:

**Data Analysis -> Data Preprocessing -> Feature Standardization -> Train-Test Split -> Model Training -> Evaluation -> Prediction**

A **Support Vector Machine (SVM)** classifier with a linear kernel was used for the classification task.

## Observations

The analysis showed noticeable differences between diabetic and non-diabetic groups, particularly in features such as **Glucose, BMI, Age, Insulin, and DiabetesPedigreeFunction**.

## Model Performance

The trained SVM model achieved the following accuracy:

| Dataset       |   Accuracy |
| ------------- | ---------: |
| Training Data | **78.66%** |
| Testing Data  | **77.27%** |

The model was also used to demonstrate prediction on a new patient input.

## Findings

The model was able to classify diabetes outcomes with **77.27% accuracy on the testing data**.

The close training and testing accuracy also provided a practical example of evaluating how a trained model performs on unseen data.

## Conclusion

This project successfully implemented a complete machine learning workflow for diabetes prediction, from dataset analysis and preprocessing to model training, evaluation, and prediction.

It provided practical experience with **binary classification, feature standardization, Support Vector Machines, train-test splitting, and model evaluation**.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Support Vector Machine (SVM)
* StandardScaler
* Google Colab / Jupyter Notebook

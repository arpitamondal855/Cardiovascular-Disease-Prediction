# Cardiovascular Disease Prediction

A machine learning mini project for predicting cardiovascular disease using patient health data.

##  Project Overview

This project focuses on analyzing cardiovascular health data and building machine learning classification models to predict whether a patient has cardiovascular disease.

The project includes:

* Data loading and understanding
* Exploratory Data Analysis (EDA)
* Data preprocessing
* Missing value handling
* Feature preparation
* Train-test splitting
* Feature scaling
* Machine learning model training
* Model evaluation
* Data visualization
* Feature importance analysis

##  Machine Learning Models

Two classification algorithms are used in this project:

1. Logistic Regression
2. Decision Tree Classifier

The Decision Tree model is configured with a maximum depth of 5 to help reduce overfitting.

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

##  Dataset

The project uses the following dataset:

`cardio_data_processed.csv`

The dataset contains health-related features used for cardiovascular disease prediction.

The target variable is:

`cardio`

##  Exploratory Data Analysis

The project performs several EDA tasks, including:

* Target variable distribution
* Feature histograms
* Correlation heatmap
* Dataset shape and data type analysis
* Missing value analysis
* Summary statistics

##  Data Preprocessing

The preprocessing steps include:

* Removing the `id` column
* Replacing invalid `no` values with missing values
* Converting relevant columns to numeric values
* Converting age from days to years
* Filling missing numerical values using median values
* Encoding categorical variables
* Separating features and target variable
* Splitting the dataset into training and testing sets
* Standardizing the features

##  Model Training

### Logistic Regression

Logistic Regression is used as one of the classification models for predicting cardiovascular disease.

### Decision Tree

A Decision Tree Classifier is also trained with:

```python
max_depth=5
random_state=42
```

##  Model Evaluation

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix
* ROC Curve

##  Visualizations

The project generates:

* Cardiovascular disease distribution chart
* Feature histograms
* Correlation heatmap
* Logistic Regression confusion matrix
* Decision Tree confusion matrix
* ROC curve comparison
* Decision Tree feature importance chart

##  How to Run the Project

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder

```bash
cd Cardiovascular-Disease-Prediction
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Python File

```bash
python cardio_prediction.py
```

##  Project Structure

```text
Cardiovascular-Disease-Prediction/
│
├── cardio_data_processed.csv
├── cardio_prediction.py
├── README.md
├── requirements.txt

```

##  Project Objective

The main objective of this mini project is to demonstrate the application of machine learning techniques for cardiovascular disease prediction, including data analysis, preprocessing, model development, evaluation, and visualization.

##  Author

** Arpita Mondal **

Department of Computer Science & Engineering  
Daffodil International University
---

⭐ If you find this project useful, feel free to star the repository.

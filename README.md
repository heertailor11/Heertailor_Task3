# Wine Quality Prediction using Machine Learning

## Overview

This project focuses on predicting wine quality using Machine Learning techniques. The dataset contains various physicochemical properties of wine, such as acidity, alcohol content, density, pH, and sulphates. The goal is to classify wines as **Good Quality** or **Bad Quality** based on these features.

The project includes data exploration, visualization, preprocessing, model training, and performance evaluation.

---

## Dataset

The project uses the **WineQT Dataset** (`WineQT.csv`).

### Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality (Target Variable)

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Import dataset using Pandas.
* Inspect dataset structure and contents.

### 2. Exploratory Data Analysis (EDA)

#### Dataset Inspection

* Dataset shape
* Data types
* Statistical summary
* Missing value analysis

#### Data Visualization

* Wine Quality Distribution
* Correlation Heatmap
* Acidity vs Quality
* Alcohol vs Quality
* Density vs Quality

These visualizations help identify important relationships between wine attributes and quality scores.

---

### 3. Data Preprocessing

#### Quality Classification

The original quality scores are converted into a binary classification problem:

* Quality ≥ 7 → Good Wine (1)
* Quality < 7 → Bad Wine (0)

#### Feature Selection

* Separate features (`X`)
* Separate target variable (`y`)

#### Data Scaling

* Standardization using `StandardScaler`

#### Train-Test Split

* Split dataset into training and testing sets.

---

## Machine Learning Models

The following classification algorithms are implemented:

### Random Forest Classifier

* Ensemble learning approach
* Handles complex feature interactions
* Provides high prediction accuracy

### SGD Classifier

* Efficient for large datasets
* Fast training process
* Linear classification model

### Support Vector Machine (SVM)

* Effective for binary classification
* Creates optimal decision boundaries

---

## Model Evaluation

Performance is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Evaluation Metrics

* Precision
* Recall
* F1-Score
* Accuracy

These metrics help assess the effectiveness of each model.

---

## Project Structure

```text
├── Oasis3.ipynb
├── WineQT.csv
├── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/wine-quality-prediction.git
```

### Navigate to Project Directory

```bash
cd wine-quality-prediction
```

### Install Required Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook Oasis3.ipynb
```

Run all notebook cells sequentially to perform:

1. Data Analysis
2. Visualization
3. Data Preprocessing
4. Model Training
5. Performance Evaluation

---

## Key Insights

* Alcohol content shows a strong relationship with wine quality.
* Certain acidity measures influence quality ratings.
* Correlation analysis helps identify the most important predictive features.
* Machine Learning models can effectively classify wine quality based on physicochemical characteristics.

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Cross-validation for robust evaluation.
* Feature importance analysis.
* Deployment using Flask or Streamlit.
* Comparison with advanced boosting models such as XGBoost and LightGBM.

---

## Learning Outcomes

Through this project, you will learn:

* Exploratory Data Analysis (EDA)
* Data Visualization Techniques
* Data Preprocessing
* Feature Scaling
* Binary Classification
* Model Evaluation
* Machine Learning Workflow with Scikit-learn

---

## Author

Developed as part of a Machine Learning project for Wine Quality Prediction using Python and Scikit-learn.

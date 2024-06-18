# Supervised Learning Task: Flow Implementation

## Overview
This project involves implementing a supervised learning model classification as part of an assignment for our data science course. The assignment covers various aspects of machine learning, from data loading and exploratory data analysis to feature engineering, model training, and evaluation.

## Steps and Components

### 1. Data Loading
- **Objective**: Load the `wine_train.csv` and `wine_test.csv` datasets.
- **Steps**:
  - Load the datasets without further splitting.
  - Display the first 5 rows of each dataset.

### 2. Exploratory Data Analysis (EDA)
- **Objective**: Conduct initial data analysis to understand the dataset.
- **Steps**:
  - Present at least 2 tables and 2 visualizations.
    
### 3. Feature Engineering
- **Objective**: Enhance the dataset by applying feature engineering techniques.
- **Steps**:
  - Apply at least one type of feature engineering metric.
  - Experiment with multiple feature engineering techniques.
  - Advanced feature engineering for additional insights.

### 4. Model Training
- **Objective**: Train machine learning models using different algorithms and hyperparameters.
- **Steps**:
  - Evaluate at least 2 learning algorithms.
  - Experiment with different hyperparameters.
  - Provide additional explanations for new algorithms or hyperparameters.

### 5. Optimal Parameter Selection
- **Objective**: Select the best combination of feature engineering, learning model, and hyperparameters.
- **Steps**:
  - Use 5-fold cross-validation and grid search.
  - Evaluate models based on \( R^2 \) for regression or F1 score for classification.
  - Present a summary table comparing the results.

### 6. Flow Implementation with Chosen Parameters
- **Objective**: Train the entire `train` dataset using the best parameters.
- **Steps**:
  - Use the best combination identified in the previous step.

### 7. Model Application on Test Set and Evaluation
- **Objective**: Apply the selected model to the `test` data and evaluate its performance.
- **Steps**:
  - Apply feature engineering to the `test` data.
  - Predict outcomes using the selected model.
  - Show the first few predictions on the `test` set.
  - Evaluate the model's performance on the `test` set.

## Repository Structure
- **data**
  - `wine_train.csv`
  - `wine_test.csv`
- **notebooks**
  - `assignment2.ipynb` - the project file
 
## How to Run
1. **Clone the Repository**
   ```bash
   git clone https://github.com/DvirUliel/Machine-learning-project.git
   cd supervised-learning-task

# Churn Prediction with Random Forest
## Project Overview
This project focuses on predicting customer churn using machine learning. A Random Forest model is trained to classify customers as "churn" or "not churn" based on various features from the Telco-Customer-Churn dataset.

## Features
- Data preprocessing and cleaning.
- Handling missing values effectively.
- Feature encoding and scaling.
- Building a classification model using the Random Forest algorithm.


## Getting Started
### Dataset
The dataset used in this project is:
- **Name:** Telco Customer Churn Dataset
- **File:** WA_Fn-UseC_-Telco-Customer-Churn.csv

### Prerequisites
Install the necessary Python libraries:
```
pip install pandas scikit-learn numpy
```

## Structure
1. Data Exploration:
    - Load the dataset and inspect its structure.
    - Check for missing values and handle them appropriately.
2. Feature Engineering:
    - Convert categorical columns to numeric.
    - Standardize numerical features.
3. Model Training:
    - Split the data into training and testing sets.
    - Train a Random Forest classifier to predict customer churn.
4. Evaluation:
    - Assess the model’s performance using metrics like accuracy and F1-score.


## How to Run
1. Clone the repository:
```
git clone <repository_url>
```
2. Navigate to the project directory:
```
cd <project_directory>
```
3. Run the Jupyter Notebook:
```
jupyter notebook churn-prediction-with-rf.ipynb
```


## Acknowledgments
This project was developed together with [Berkay Derin](https://github.com/berkayderin). We worked as a team to build this solution.


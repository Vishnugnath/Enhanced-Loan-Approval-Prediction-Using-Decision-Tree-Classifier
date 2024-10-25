
# Enhanced Loan Approval Prediction Using Decision Tree Classifier

## Overview

This project aims to predict loan approval status using a Decision Tree Classifier. By analyzing various features related to loan applicants, we can classify whether a loan application is likely to be approved or rejected.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Feature Importance](#feature-importance)
- [Prediction on New Data](#prediction-on-new-data)
- [License](#license)

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset used in this project is `loan_approval_dataset.csv`, which contains various features associated with loan applications. The features include:

- Loan ID
- Number of Dependents
- Education Level
- Self-employed Status
- Annual Income
- Loan Amount
- Loan Term
- CIBIL Score
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Asset Value
- Loan Status (Target Variable)

Dataset Location: `dataset/loan_approval_dataset.csv`

## Usage

To run the Jupyter Notebook, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Vishnugnath/Enhanced-Loan-Approval-Prediction-Using-Decision-Tree-Classifier.git
   cd Enhanced-Loan-Approval-Prediction-Using-Decision-Tree-Classifier
   ```

2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Enhanced\ Loan\ Approval\ Prediction\ Using\ Decision\ Tree\ Classifier.ipynb
   ```

4. Execute the notebook cells to load the data, train the model, evaluate its performance, and make predictions.

## Model Evaluation

The model is evaluated using:
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- Cross-validation scores

## Feature Importance

A bar plot visualizes the importance of different features in predicting loan approval status.

## Prediction on New Data

The model can be used to predict loan approval for new applicants by providing relevant input features. An example is included in the notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

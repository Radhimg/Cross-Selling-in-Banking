# Cross-Selling-in-Banking
A machine learning project for predicting financial product preferences based on customer demographics and income.

## Description

The project involves generating synthetic data, augmenting the data, preprocessing it, training various machine learning models, and evaluating their performance. The models used include Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machines (SVM).

## Project Workflow

1. **Generate Data**: Synthetic customer data is generated using numpy and pandas.
2. **Data Augmentation**: The initial dataset is augmented to create a larger dataset.
3. **Data Preprocessing**: Categorical variables are converted into numerical representations.
4. **Model Training**: Multiple machine learning models are trained using GridSearchCV to find the best hyperparameters.
5. **Evaluation**: Models are evaluated based on accuracy and other metrics.
6. **Prediction**: The best model is used to predict new customer preferences.

## Viewing the Notebook

You can view the Jupyter Notebook through nbviewer using the following link:

[View Notebook in nbviewer](https://nbviewer.jupyter.org/github/Radhimg/Cross-Selling-in-Banking/blob/main/Cross%20Selling%20in%20Banking.ipynb)

## Running the Project Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Radhimg/Cross-Selling-in-Banking.git
   cd Cross-Selling-in-Banking

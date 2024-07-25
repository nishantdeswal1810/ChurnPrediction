# Churn Prediction Project

## Overview

This project aims to predict customer churn for a telecommunications company using an Artificial Neural Network (ANN) model. The dataset includes customer information from three countries: France, Spain, and Italy. The project involves data preprocessing, feature engineering, model training, and deploying a Streamlit app for interactive predictions.

## Installation

To run this project locally, you need to set up a Python environment and install the required dependencies.

1. **Clone the repository**:
    ```bash
    git clone https://github.com/nishantdeswal1810/ChurnPrediction.git
    cd ChurnPrediction
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

    This will start a local web server. Open your browser and navigate to `http://localhost:8501` to access the app.

2. **Exploratory Data Analysis**:
    - Open and run `experiments.ipynb` to explore the dataset and visualize different features.

3. **Model Training and Hyperparameter Tuning**:
    - Use `hyperparametertuningann.ipynb` for tuning the ANN model hyperparameters.
    - The final model is saved as `model.h5`.

4. **Prediction**:
    - Run `prediction.ipynb` to make predictions using the trained model.

## Dataset

The dataset (`Churn_Modelling.csv`) contains the following columns:
- RowNumber
- CustomerId
- Surname
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (target variable)

## Feature Engineering

Feature engineering steps include:
- Encoding categorical variables (Gender and Geography).
- Scaling numerical features.
- Creating new features if necessary.

## Model

The ANN model is built using the following steps:
1. Input layer with appropriate input dimensions.
2. Hidden layers with ReLU activation.
3. Output layer with sigmoid activation for binary classification.

## Results

The performance of the model is evaluated using accuracy, precision, recall, and F1-score. Hyperparameter tuning helps in optimizing the model for better performance.

## Conclusion

This project demonstrates how to build and deploy a machine learning model for predicting customer churn. The Streamlit app provides an interactive interface for making predictions and understanding the model's output.

## Future Work

- Improve the model by trying different architectures or algorithms.
- Enhance the Streamlit app with more features and visualizations.
- Deploy the app to a cloud platform for wider accessibility.

## Contact

For any questions or suggestions, please reach out to:

- **Nishant Deswal**
- Email: nishantdeswal702@gmail.com
- LinkedIn: [Nishant Deswal](https://www.linkedin.com/in/nishant-deswal-4204ba256/)

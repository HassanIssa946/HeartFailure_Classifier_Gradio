# HeartFailure_Classifier_Gradio

This project provides a web interface for predicting the likelihood of heart failure based on clinical records using a logistic regression model. The interface is built using Gradio and allows users to input various medical parameters to receive a prediction.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Features](#features)



## Overview

The HeartFailure_Classifier_Gradio project aims to provide an easy-to-use web interface for predicting heart failure using clinical data. The prediction is made using a logistic regression model trained on a dataset of heart failure clinical records. The web interface is implemented using Gradio, a Python library for creating interactive web interfaces.

## Installation

To run this project locally, follow these steps:

 **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/HeartFailure_Classifier_Gradio.git
    cd HeartFailure_Classifier_Gradio
    ```

1. **Create a virtual environment:**

    ```sh
    python -m venv venv
    On mac source venv/bin/activate  
    On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    Create a `requirements.txt` file with the following content:

    ```
    pandas
    numpy
    matplotlib
    scikit-learn
    gradio
    ```

    Then run:

    ```
    pip install -r requirements.txt
    ```

4. **Download the dataset:**

    Place your `heart_failure_clinical_records_dataset.csv` file in the project directory.

## Usage

To run the Gradio interface, execute the following command:


run the last cell in the notebook 

## Model Details

### Logistic Regression

**Description**: The model used in this project is a Logistic Regression classifier. Logistic Regression is a statistical method for binary classification that models the probability of a binary outcome based on one or more predictor variables.

**Hyperparameters**:
- **Solver**: `lbfgs` (Limited-memory Broyden-Fletcher-Goldfarb-Shanno) is used for optimization.
- **Max Iterations**: `1000` (The maximum number of iterations taken for the solvers to converge).

**Performance**:
- **Training Accuracy**: Provides the accuracy of the model on the training dataset.
- **Testing Accuracy**: Provides the accuracy of the model on the testing dataset.

The model is trained on a dataset of heart failure clinical records, where it learns to predict whether a patient is likely to experience heart failure based on various medical parameters.


## Features

- **Interactive Web Interface**: Users can input various medical parameters through an easy-to-use Gradio web interface.
- **Prediction**: The interface provides a prediction of heart failure based on the entered clinical data.
- **Medical Parameters**: The model takes into account several medical attributes, including age, blood pressure, and more.
- **Responsive Design**: The web interface is designed with a medical theme and a white background to ensure clarity and usability.




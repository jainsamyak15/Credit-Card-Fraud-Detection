# Credit-Card-Fraud-Detection
This project aims to build and evaluate machine learning models for detecting fraudulent credit card transactions. By leveraging historical transaction data, the goal is to train classification models that can accurately identify fraudulent transactions, enabling financial institutions to prevent potential losses and enhance security measures.

## Dataset

The project utilizes a real-world dataset containing credit card transactions made by European cardholders in September 2013. The dataset includes features related to each transaction, as well as a binary target variable indicating whether the transaction was fraudulent or legitimate.

## Models

The following classification models are implemented and evaluated in this project:

1. **Decision Tree Classifier**
2. **Support Vector Machine (SVM)**

Both Scikit-learn and Snap ML libraries are used to build and train these models, allowing for a comparative analysis of performance and training times.

## Evaluation Metrics

The trained models are evaluated using the following metrics:

- **ROC-AUC (Area Under the Receiver Operating Characteristic Curve)**: A performance metric that measures the ability of the model to distinguish between classes.
- **Hinge Loss**: A loss function used for evaluating the performance of SVM models.

## Dependencies

The following libraries are required to run the project:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Snap ML

## Usage

1. Clone the repository:`git clone https://github.com/jainsamyak15/Credit-Card-Fraud-Detection.git`
2. Install the required dependencies:`pip install -r requirements.txt`
3. Run the Jupyter Notebook or Python script containing the project code



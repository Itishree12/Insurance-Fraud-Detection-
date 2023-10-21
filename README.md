# Insurance Claim Detection Machine Learning Model

## Overview

This repository contains the code and resources for an insurance claim detection machine learning model. The primary goal of this project is to build a predictive model that can identify whether a given insurance claim is fraudulent or legitimate. The project includes data preprocessing, exploratory data analysis (EDA), feature selection, model development, and evaluation.

## Project Structure

The project is organized as follows:

- `Data/`: Contains the dataset used for model training.
- `EDA/`: Jupyter notebooks used for EDA.
- `Model/`: Python source code for data preprocessing, feature selection, and model development.
- `README.md`: Overview of the project.

## Data

The dataset used for this project is located in the directory Datset. It includes information related to insurance claims, such as claimant details, policy information, and the outcome of the claim (fraudulent or not). The dataset is split into training and testing sets.

## EDA (Exploratory Data Analysis)

The `EDA/Fraud Detection EDA.ipynb` notebook contains the EDA process. It includes data visualization, statistical analysis, and insights into the dataset. EDA helps in understanding the data, identifying patterns, and uncovering potential features that can be used for model development.


## Feature Selection

Feature selection is a crucial step in building an effective machine learning model. The `Model/Fraud detection model.ipynb` notebook explores different feature selection techniques, including statistical tests and feature importance from machine learning models. The selected features are then used for model development.

## Model Development

The machine learning model is developed in the `Model/Fraud detection model.ipynb` notebook. Various algorithms are tested and evaluated for their ability to predict fraudulent insurance claims. Hyperparameter tuning and model optimization are performed to enhance predictive performance.

## Model Evaluation


The model is evaluated using standard machine learning metrics such as accuracy, precision, recall, F1-score, and ROC AUC. The evaluation results are presented in the respective notebooks.

## Screenshots

![Screenshot 2023-10-21 at 3 19 04 PM](https://github.com/Itishree12/Insurance-Fraud-Detection-/assets/121350293/bcc5a6cd-1099-46df-908c-e6049be5d377)

![Screenshot 2023-10-21 at 3 22 32 PM](https://github.com/Itishree12/Insurance-Fraud-Detection-/assets/121350293/ef5934d8-0a18-4ac8-95c9-e1c0cb38cfe0)


## How to Run

To run this project on your local machine, follow these steps:

1. Clone this repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd insurance-claim-detection`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Open and run the Jupyter notebooks in the `notebooks/` directory in the specified order (EDA, Feature_Selection, Model_Development).

## Dependencies

This project relies on various Python libraries and packages. The primary dependencies can be found in the `requirements.txt` file. You can install them using `pip`.
## Installation

Install my-project with npm

```bash
pip install numpy 
```
```bash  
pip install pandas 
```
```bash  
pip install scikit-learn  
```
```bash  
pip install matplotlib  
```
```bash  
pip install seaborn  
```
```bash  
pip install xgboost lightgbm
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- ITISHREE SAMAL

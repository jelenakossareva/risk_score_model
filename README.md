# ML Risk Score Modeling for Cryptocurrency Exchange Platform

This project focuses on developing machine learning models that predict a score for customers based on various features. The score represents the risk associated with each customer, enabling managers to pay more attention to risky customers. By accurately assessing the risk associated with each client, the platform can take appropriate measures to ensure the security and integrity of its operations.

## Technologies Used

- Python 3.11.4

## Installation

To run the ML Risk score modeling project, please follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the cloned directory.
3. Ensure that Python 3.x is installed on your system.
4. Install the required dependencies by running pip install -r requirements.txt.
5. Start the Jupyter Notebook server by running the following command: ```jupyter notebook```
6. In the Jupyter Notebook interface, you will see the file browser. Click on the IPython Notebook file score_model.ipynb.
7. The IPython Notebook will open in a new tab, displaying the notebook's contents, including code cells and markdown cells.
8. To run a code cell, click on the cell to select it, then press Shift + Enter or click the "Run" button in the toolbar. The code will be executed, and the output (if any) will be displayed below the cell.
9. Continue running the code cells in the notebook as needed. You can also edit the code and rerun cells to experiment and iterate.
10. To stop the Jupyter Notebook server, go back to the terminal or command prompt where the server is running and press Ctrl + C. Confirm by entering y if prompted.

## Features
The dataset used for ML score modeling includes the following features:

- **Customer ID**: A unique identifier for each customer.
- **Age**: The age of the customer.
- **Date of Birth Same Country Residence**: Indicates whether the customer's country of birth is the same as the country of residence (yes/no; 1/0).
- **Nationality Same Country Residence**: Indicates whether the customer's nationality is the same as the country of residence (yes/no; 1/0).
- **Date of Birth Same Nationality**: Indicates whether the customer's date of birth is the same as other customers of the same nationality (yes/no; 1/0).
- **Phone Country Same Residence**: Indicates whether the customer's phone country is the same as the country of residence (yes/no; 1/0).
- **Country Residence Last IP**: Indicates whether the customer's country of residence is the same as the country associated with the last IP address (yes/no; 1/0).
- **Corruption Perception Index**: Transparency agency's corruption perception index.
- **IP Diversity**: Indicates whether there is diversity in IP addresses used by the customer (yes/no; 1/0).
- **User Agent Diversity**: Indicates whether there is diversity in user agents used by the customer (yes/no; 1/0).
- **Location Diversity**: Indicates whether there is diversity in locations associated with the customer (yes/no; 1/0).
- **Unknown Transaction Rate**: The ratio of unknown transactions to all transactions made by the user to get cryptocurrency to their own wallet.
- **Low Risk Transaction Rate**: The ratio of low-risk transactions (income-outcome from another cryptocurrency platform) to all transactions made by the user.
- **High Risk Transaction Rate**: The ratio of high-risk transactions (gambling, stolen wallets) to all transactions made by the user.
- **Fail Transaction Rate**: The ratio of failed transactions to all transactions made by the user.

## Usage

Here is a brief overview of their usage:
1. Data Preparation: This notebook focuses on data preprocessing, including handling missing values, feature engineering, and data cleaning. It prepares the dataset for subsequent modeling steps.
2. Exploratory Data Analysis: This notebook explores the dataset, performs statistical analysis, and visualizes key patterns and relationships among the features. It provides insights into the characteristics of the data and helps identify potential correlations.
3. Model Development: This notebook involves training and evaluating machine learning models using the selected features. Several algorithms, such as k Nearest Neighbors (kNN), decision tree, random forests, and Support Vector Classifier (SVC), are implemented to predict the risk score. These algorithms were chosen for their ability to handle classification tasks and their potential to capture the complex relationships in the dataset.



# Building a Demand Forecasting Model using PySpark

## Overview
This project aims to build a demand forecasting model using PySpark. The main features of the project include data preprocessing, feature engineering, and training a Random Forest regression model to predict future sales.

## Setup Instructions
To set up the project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/harshitIIITD/building-a-demand-forecasting-model-using-pyspark-datacamp.git
   ```
2. Navigate to the project directory:
   ```
   cd building-a-demand-forecasting-model-using-pyspark-datacamp
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Jupyter Notebook
To run the Jupyter notebook, follow these steps:

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Open the `notebook.ipynb` file in the Jupyter Notebook interface.
3. Run the cells in the notebook sequentially to execute the code.

## Dataset
The dataset used in this project is `Online Retail.csv`. It contains transactional data for an online retail store. The dataset includes columns such as `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`. The source of the dataset is the UCI Machine Learning Repository.

## Interpreting the Results
The results of the demand forecasting model can be interpreted by analyzing the predicted sales quantities. The Mean Absolute Error (MAE) is used to evaluate the model's performance. Potential improvements to the model could include trying different machine learning algorithms, tuning hyperparameters, and incorporating additional features.

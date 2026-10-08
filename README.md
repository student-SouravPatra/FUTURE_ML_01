\# Sales \& Demand Forecasting for Businesses



\## Future Interns - Machine Learning Internship



\### Task 1: Sales \& Demand Forecasting



This project focuses on forecasting future monthly sales using historical sales data.



\## Objective



The objective is to analyze historical sales data, identify sales trends, build a forecasting model, evaluate its performance, and generate a 6-month future sales forecast.



\## Dataset



Dataset: Sample Superstore



The dataset contains business transaction information such as:



\- Order Date

\- Ship Date

\- Customer

\- Segment

\- Category

\- Sales

\- Quantity

\- Discount

\- Profit



Historical period:

January 2014 to December 2017



Total records:

9,994



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Scikit-learn

\- Jupyter Notebook



\## Project Workflow



1\. Load the dataset

2\. Explore the dataset

3\. Check missing values and duplicate records

4\. Convert date columns

5\. Aggregate sales by month

6\. Create time-based features

7\. Split data chronologically into training and testing sets

8\. Train a Linear Regression model

9\. Generate sales predictions

10\. Evaluate the model using MAE, MSE and RMSE

11\. Perform error analysis

12\. Generate a 6-month sales forecast

13\. Visualize historical and forecasted sales

14\. Extract business insights



\## Model



A Linear Regression model was used with:



\- Time Index

\- Month



as the main time-based features.



The model provides a baseline estimate of future monthly sales.



\## Model Evaluation



\- MAE: $11,599.75

\- RMSE: $17,017.19



\## Business Insights



The analysis provides historical sales trends and a 6-month future sales forecast that can support:



\- Inventory planning

\- Demand planning

\- Sales planning

\- Business decision-making



\## Project Structure



```text

FUTURE\_ML\_01/

│

├── data/

│   └── Sample - Superstore.csv

│

├── notebooks/

│   └── Sales\_Demand\_Forecasting.ipynb

│

├── visuals/

│

├── requirements.txt

│

└── README.md


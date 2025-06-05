This project demonstrates a basic stock price prediction model using Linear Regression. It leverages historical stock data to predict the closing price based on opening price, highest price, lowest price, and trading volume.

Project Structure
HistoricalData_1749094856837.csv: The dataset containing historical stock prices.
Jupyter Notebook (e.g., stock_prediction.ipynb): The main notebook containing the Python code for data loading, preprocessing, model training, evaluation, and visualization.
Features
Data Cleaning and Preprocessing: Handles missing values, converts data types, and formats the dataset for analysis.
Exploratory Data Analysis (EDA): Visualizes the correlation between different stock attributes using a heatmap.
Linear Regression Model: Implements a simple linear regression model to predict stock closing prices.
Model Evaluation: Assesses the model's performance using Mean Squared Error (MSE) and R-squared (R 
2
 ).
Visualization: Plots actual vs. predicted stock prices to visually inspect the model's accuracy.
Getting Started
Prerequisites
Make sure you have the following Python libraries installed:

Bash

pip install pandas numpy matplotlib seaborn scikit-learn
How to Run
Download the project files: Ensure you have the Jupyter Notebook file and HistoricalData_1749094856837.csv in the same directory.
Open the Jupyter Notebook:
Bash

jupyter notebook
Run all cells: Execute all cells in the notebook sequentially to perform data loading, preprocessing, model training, and evaluation.
Results
The trained Linear Regression model achieved the following performance metrics on the test set:

Mean Squared Error (MSE): 1.39
R-squared (R 
2
 ): 0.9976
These metrics indicate that the model performs exceptionally well in predicting the closing stock prices, explaining approximately 99.76% of the variance in the closing price.

Visualization
The notebook includes a plot comparing the actual stock prices with the predicted prices, providing a visual representation of the model's accuracy over time.

Feel free to explore the notebook, modify the code, or experiment with other machine learning models for stock price prediction!

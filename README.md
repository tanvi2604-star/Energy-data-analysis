# Energy-data-analysis
Energy Consumption Analysis – Machine Learning Project
Project Overview

This project focuses on analyzing and predicting energy consumption using synthetic dataset generation, data preprocessing, visualization, and machine learning techniques.
It demonstrates the process of working with data from raw form to meaningful insights.

 Steps Implemented

Data Generation

Created synthetic data (Date, Energy Consumption, Temperature, Appliance Usage).

Saved data into a CSV/Excel file for analysis.

Data Cleaning & Preprocessing

Handled missing values.

Converted date column to datetime format.

Extracted Month and DayOfWeek for analysis.

Exploratory Data Analysis (EDA)

Plotted trends of energy consumption over time.

Visualized correlation between energy consumption, temperature, and appliance usage.

Checked monthly and weekly consumption averages.

Model Building

Applied Linear Regression to predict energy consumption.

Trained the model with 80% data, tested on 20%.

Evaluated using R² score and Mean Squared Error (MSE).

Results

Model successfully predicts energy consumption trends.

Data visualizations highlight important insights such as:

Energy consumption peaks in certain months.

Strong relation between temperature and consumption.

 Tech Stack

Language: Python

Libraries: pandas, numpy, matplotlib, scikit-learn

Tool: Jupyter Notebook

Output: CSV/Excel + Graphs

 Project Files

energy_analysis.ipynb → Jupyter Notebook with complete code

energy_data.xlsx → Final cleaned dataset

presentation.pdf → Project summary for internship submission

README.md → Project documentation (this file)

 How to Run the Project

Clone this repository or download the files.

Install dependencies:

pip install pandas numpy matplotlib scikit-learn


Open the Jupyter Notebook:

jupyter notebook energy_analysis.ipynb


Run all cells to generate dataset, clean it, visualize, and train the model.

 Sample Output

Line chart showing energy consumption over time.

Scatter plot of Temperature vs Consumption.

Predicted vs Actual energy usage comparison.

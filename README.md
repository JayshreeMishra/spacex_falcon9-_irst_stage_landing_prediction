# SpaceX Falcon 9 First Stage Landing Prediction: A Data Science Capstone Project

## Project Overview
This project focuses on predicting the landing success of SpaceX Falcon 9 first-stage rockets. The process involves data collection, data wrangling, exploratory data analysis (EDA), and machine learning modeling. The project utilizes a variety of technologies and tools, including HTTP requests, Beautiful Soup for web scraping, Pandas DataFrames for data manipulation, SQL for analysis, and machine learning algorithms such as logistic regression, SVM, decision trees, and KNN for prediction.

## Project is Divided into Six Parts:
1. **Data Collection:**
   - The script collects SpaceX Falcon 9 performance data from a Wikipedia page using HTTP requests and Beautiful Soup. The data is then stored in Pandas DataFrames and saved to a CSV file.

2. **Data Wrangling:**
   - This section involves importing necessary libraries, reading CSV data, and performing operations like handling missing values, creating new columns, and calculating success rates. The cleaned data is saved to a new CSV file.

3. **Exploratory Data Analysis (EDA) with SQL:**
   - The EDA is conducted using SQL queries on the cleaned data. Various analyses, including payload mass calculations, launch site exploration, and success rates over time, are performed.

4. **EDA and Feature Engineering:**
   - This part of the project focuses on visualizing relationships between different variables, exploring success rates, and creating new features. The final dataset with engineered features is saved to a CSV file.

5. **Launch Sites Locations Analysis with Folium:**
   - This section analyzes the locations of SpaceX launch sites using Folium. It includes mapping the launch sites, determining marker colors based on outcomes, and exploring points of interest near launch sites.

6. **Machine Learning Prediction:**
   - Machine learning models (logistic regression, SVM, decision tree, KNN) are trained and evaluated for predicting SpaceX Falcon 9 landing success. The project compares the models based on accuracy scores and generates confusion matrices.

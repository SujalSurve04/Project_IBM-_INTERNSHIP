# Project_IBM-_INTERNSHIP
# Airbnb Listings Analysis in New York City

## Overview
This project analyzes Airbnb listings in New York City to gain insights into the rental market, understand pricing trends, and identify factors that affect listing popularity. The analysis includes exploratory data analysis (EDA), feature engineering, model building using linear regression, and model evaluation.

## Dataset
The dataset used in this project is the "AB_NYC_2019.csv" file, which contains Airbnb listings in New York City. It includes various attributes such as listing price, location, number of reviews, room type, and neighborhood group.

## Project Structure
- `project.ipynb`: Jupyter Notebook containing the Python code for the data analysis.
- `AB_NYC_2019.csv`: Dataset file containing Airbnb listings data.
- `README.md`: This file providing an overview of the project.

## Libraries Used
- Pandas: Data manipulation and analysis.
- Matplotlib: Data visualization.
- Seaborn: Data visualization.
- Scikit-learn: Machine learning model building and evaluation.

## Key Steps
1. **Data Loading and Exploration**:
   - Load the dataset into a Pandas DataFrame.
   - Perform basic data exploration and check for missing values.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of listing prices.
   - Explore the relationship between listing price and other variables such as number of reviews, room type, and neighborhood group.

3. **Feature Engineering**:
   - Create new features if needed.
   - Encode categorical variables.

4. **Model Building**:
   - Select relevant features and target variable.
   - Split the data into training and testing sets.
   - Train a linear regression model to predict listing prices.
   - Evaluate the model's performance using mean absolute error, mean squared error, and R-squared score.

5. **Model Interpretation and Conclusion**:
   - Interpret the coefficients/features to understand factors influencing listing prices.
   - Summarize the findings and outcomes of the analysis.

## Author
- Sujal Surve
- Contact : survesujal104@gmail.com

## Conclusion
This project provides valuable insights into the Airbnb rental market in New York City. By analyzing listing data and building a predictive model, we can better understand pricing trends and factors affecting listing popularity. The model's performance suggests its potential utility for hosts and potential guests in the Airbnb ecosystem.

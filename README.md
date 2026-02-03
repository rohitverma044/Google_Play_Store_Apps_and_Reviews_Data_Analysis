# Google_Play_Store_Apps_and_Reviews_Data_Analysis

This project performs in-depth analysis of Google Play Store applications using Python. It includes data cleaning, exploratory data analysis (EDA), visualization, sentiment analysis of user reviews, time-based update trends, and machine learning-based rating prediction.

The goal is to understand app performance patterns and extract meaningful business insights.

#  Objectives

Clean and preprocess raw Google Play Store data

Analyze app ratings, installs, price, and categories

Visualize trends and distributions

Perform sentiment analysis on user reviews

Analyze app update patterns over time

Build a machine learning model to predict app ratings

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

# Dataset Information
Main Dataset

Google Play Store Apps Dataset
Includes:

App Name

Category

Rating

Reviews

Size

Installs

Price

Type (Free/Paid)

Last Updated

Review Dataset

Includes:

User Reviews

Translated Reviews

Sentiment Labels

# Data Cleaning Steps

The following preprocessing steps were applied:

Removed invalid ratings (> 5)

Converted Reviews column to integer

Cleaned Installs column by removing + and ,

Converted Price to float

Converted Size values into MB

Handled missing values

Converted date columns to datetime format

# Exploratory Data Analysis (EDA)
Key Visualizations Created:

Distribution of App Ratings

App Count by Category

Rating vs Installs Scatter Plot

Free vs Paid Apps Comparison

Price vs Rating Box Plot

Correlation Heatmap

Sentiment Distribution Graph

App Updates Per Year Trend

# Sentiment Analysis

User reviews were analyzed to understand customer feedback.

Sentiment Categories:

Positive

Neutral

Negative

A bar chart visualization was created to show sentiment distribution.

# Time-Based Analysis

App update trends were analyzed using:

Year of update

Monthly update patterns

This helps understand update frequency behavior of apps over time.

# Machine Learning Model
Model Objective

Predict app ratings based on numerical features.

Steps Performed:

Feature selection

Train-test split

Model training

Prediction generation

Actual vs Predicted visualization

A line plot was used to compare actual and predicted ratings.

# Key Insights

Most apps fall between ratings 4.0 – 4.5

Free apps dominate the Play Store

Higher installs are generally associated with higher ratings

Positive sentiment is dominant in user reviews

App updates peaked during recent years

Correlation shows rating is influenced by reviews and installs


# Future Improvements

Deploy model as web app

Add Power BI dashboard integration

Improve ML accuracy using advanced algorithms

Perform category-wise recommendation analysis

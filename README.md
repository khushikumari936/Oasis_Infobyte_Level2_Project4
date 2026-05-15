# Google Play Store Data Analysis

## Project Overview
This project focuses on analyzing Google Play Store data to uncover insights about the Android app market. The dataset was cleaned, transformed, and analyzed using Python libraries such as Pandas, NumPy, and Matplotlib.

The project aims to understand app market trends, category distribution, user ratings, pricing patterns, app popularity, and user sentiments through data visualization and exploratory data analysis (EDA).

---

# Objectives

- Clean and preprocess Google Play Store datasets
- Analyze app categories and market distribution
- Explore app ratings, reviews, installs, pricing, and size trends
- Perform sentiment analysis on user reviews
- Create visualizations for better understanding of app market dynamics
- Improve data analytics and visualization skills

---

# Dataset Information

Dataset Source:  
https://www.kaggle.com/datasets/utshabkumarghosh/android-app-market-on-google-play

Files Used:
- apps.csv
- user_reviews.csv

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Data Cleaning Process

The following preprocessing steps were performed:

- Removed duplicate records
- Renamed unnecessary columns
- Handled missing values
- Converted data types for:
  - Reviews
  - Installs
  - Price
  - Ratings
- Cleaned special characters such as:
  - +
  - ,
  - $
- Processed categorical and numerical features

---

# Exploratory Data Analysis (EDA)

## Category Analysis
- Analyzed distribution of apps across different categories
- Identified categories with the highest number of apps

## Ratings Analysis
- Explored app rating distribution
- Calculated descriptive statistics for ratings

## Popularity Analysis
- Identified top installed applications
- Compared installs with reviews and ratings

## Pricing Analysis
- Compared free and paid applications
- Studied pricing patterns in the Play Store

## App Size Analysis
- Investigated app size distribution
- Cleaned inconsistent size formats

---

# Sentiment Analysis

User review sentiments were analyzed using the user_reviews.csv dataset.

Sentiment categories:
- Positive
- Negative
- Neutral

Visualization techniques were used to compare sentiment distribution.

---

# Visualizations Created

- Bar Charts
- Histograms
- Pie Charts
- Distribution Graphs

These visualizations helped in understanding:
- Category dominance
- User behavior
- App popularity
- Market trends

---

# Key Insights

- Most applications on the Play Store are free
- Family and Game categories contain the highest number of apps
- Apps with higher installs generally receive more reviews
- Positive user sentiments dominate the review dataset
- Paid apps represent a smaller portion of the market

---

# Project Structure

Google-Play-Store-Analysis/

│

├── apps.csv

├── user_reviews.csv

├── analysis.ipynb

├── README.md

---

# How to Run the Project

1. Clone the repository

```bash
git clone <repository-link>

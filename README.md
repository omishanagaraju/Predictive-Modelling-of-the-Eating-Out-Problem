# Zomato Sydney Data

This repository contains code for performing Exploratory Data Analysis (EDA) and building Machine Learning (ML) models. The code is written in Python, using libraries such as Pandas, Matplotlib, Plotly, Scikit-learn, and others.

#### Project Structure
eda-ml-models.ipynb: Jupyter notebook that includes data analysis and machine learning models.

data/: Directory where datasets sydney.geojson and zomato_df_final_data.csv are stored.

## Predictive Modeling of Sydney Restaurants using Zomato Data

This project focuses on analyzing and predicting the success of restaurants in Sydney using a dataset of over 10,500 restaurant records. 

The project is divided into two key parts:

Exploratory Data Analysis (EDA): Visualizations and statistical summaries are used to explore the dataset. Key insights include the number of unique cuisines, top suburbs with the most restaurants, and an analysis of the relationship between restaurant cost and ratings.

Predictive Modeling: Multiple machine learning models (regression and classification) are applied to predict restaurant ratings and success. Feature engineering and data preprocessing are done to improve model performance.

The dataset contains 10,500 records of restaurants in Sydney, with details including address, average cost, cuisine type, latitude/longitude, rating (numeric and text), number of votes, and more. The dataset is used to analyze restaurant success through features like cost, location, and ratings, and it supports machine learning applications for predictive modeling.

## Setup and Installation
1. Clone the repository:
git clone https://gitlab.com/omishanagaraju/predictive-modelling-of-the-eating-out-problem.git

2. On Terminal navigate to cd the directory predictive-modelling-of-the-eating-out-problem

2. Install the required dependencies:
pip install -r requirements.txt

## How to Run
1. Open the Jupyter notebook:
jupyter notebook eda-ml-models.ipynb.ipynb

2. Execute the notebook cells step by step to:
   
   a. Perform exploratory data analysis (EDA).

   b. Visualize key insights from the dataset.
   
   c. Create interactive plots for better visualisation experience.

   d. Train machine learning models such as linear regression, Stochastic Gradient Descent, Random Forest, Logistic Regression, Support Vector Machines, K-Nearest Neighbors.

   d. Evaluate the performance of the models on test data.

## Expected Output
**Exploratory Data Analysis:** The notebook includes various plots and statistical summaries to understand the dataset. Expect visualizations such as histograms, scatter plots, and heatmaps.

**Machine Learning Models:** The notebook trains machine learning models to predict target variables. The output will include model performance metrics such as accuracy, precision, recall, and more depending on the type of model used.

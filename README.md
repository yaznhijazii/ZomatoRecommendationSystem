# Zomato Recommendation System
<img src="res-re.jpg" alt="Resturant " width="547" height="364">
This project aims to build a restaurant recommendation system using the Zomato restaurants dataset available on Kaggle. The recommendation system suggests similar restaurants based on the user's input restaurant name.

## Introduction

The Zomato Restaurant Recommendation System is designed to help users discover new restaurants that are similar to their favorite ones. By leveraging machine learning techniques, the system analyzes various restaurant attributes such as cuisine, location, and ratings to generate personalized recommendations.

## Dataset

The dataset used in this project is sourced from Kaggle and contains information about thousands of restaurants worldwide. It includes details such as restaurant names, cuisines offered, location coordinates, average cost for two, ratings, and more.

**Dataset Link:** [Zomato Restaurants Data](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)

## Steps

### 1. Understanding and Preprocessing the Data

The dataset is loaded and cleaned to handle missing values and duplicate entries. Preprocessing steps include merging datasets, handling missing values, and feature engineering.

### 2. Exploratory Data Analysis (EDA)

Exploratory analysis is conducted to gain insights into the distribution of key features such as aggregate ratings, cuisine types, and restaurant locations. Visualizations such as histograms, bar plots, and heatmaps are used to understand the data better.

### 3. Feature Engineering

Features such as one-hot encoded cuisines, restaurant locations, and average ratings are created to train the recommendation model. The dataset is prepared for building the recommendation system.

### 4. Building the Recommendation System

A content-based filtering approach is used to build the recommendation system. Cosine similarity is calculated between restaurants based on their attributes, and similar restaurants are recommended to users based on their input.

### 5. Evaluation

The recommendation system's performance is evaluated using metrics such as precision, recall, and accuracy. The system's ability to recommend similar restaurants accurately is assessed using a test set of data.

## Usage

To use the Zomato Restaurant Recommendation System, follow these steps:

1. Install the necessary libraries listed in the requirements.txt file.
2. Download the Zomato dataset from the provided Kaggle link.
3. Run the notebook file "ZomatoReco.ipynb" in a Jupyter Notebook environment or Google Colab.
4. Follow the instructions in the notebook to preprocess the data, build the recommendation system, and evaluate its performance.
5. Input the name of a restaurant to get recommendations for similar restaurants.

## Dependencies

The project is developed using Python and relies on the following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Install these dependencies using pip:

```bash
pip install -r requirements.txt

Credits
Dataset: Zomato Restaurants Data


Feel free to adjust any details or formatting to better fit your project!



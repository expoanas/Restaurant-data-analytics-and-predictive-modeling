# Restaurant Data Analytics and Predictive Modeling

## Project Overview

This project focuses on analyzing restaurant data to understand ratings, customer preferences, pricing, cuisines, and restaurant services. The dataset was explored and cleaned using Python, followed by data visualization and predictive modeling.

The project also uses regression models to predict the **Aggregate Rating** of restaurants based on selected features.

## Objectives

* Explore and understand the restaurant dataset
* Handle missing values and prepare the data for analysis
* Analyze restaurant ratings and their distribution
* Study cuisines, cities, price ranges, table booking, and online delivery
* Create useful features from the available data
* Analyze the relationship between restaurant features and ratings
* Build regression models to predict restaurant ratings
* Compare the performance of different regression algorithms
* Create visualizations to present the findings clearly

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

### 1. Data Exploration and Preprocessing

The dataset was first loaded and examined to understand its structure. Missing values were checked and handled where required. Numerical and categorical variables were also explored.

### 2. Exploratory Data Analysis

The project analyzes:

* Distribution of restaurant ratings
* Country and city-wise restaurant information
* Popular cuisines
* Restaurant price ranges
* Table booking availability
* Online delivery availability
* Average ratings across different price ranges
* Restaurant locations using latitude and longitude

### 3. Feature Engineering

Additional features were created from the existing data, including:

* Restaurant name length
* Address length
* Table booking indicator
* Online delivery indicator

These features were then used for further analysis and modeling.

### 4. Predictive Modeling

Regression models were developed to predict the **Aggregate Rating** of restaurants.

The models used were:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

The models were evaluated using:

* Mean Squared Error (MSE)
* R-squared (R²) Score

### 5. Cuisine and Rating Analysis

The project also examines the relationship between cuisines and restaurant ratings. It identifies popular cuisines based on the number of votes and compares cuisines based on their average ratings.

### 6. Data Visualization

Different charts were created to understand and communicate the data, including:

* Histograms
* Bar charts
* Box plots
* Count plots
* Cuisine rating plots
* City-wise rating comparisons
* Feature relationship plots

## Key Areas Analyzed

| Area               | Analysis                                    |
| ------------------ | ------------------------------------------- |
| Restaurant Ratings | Distribution and frequency of ratings       |
| Cuisines           | Popular cuisines and average ratings        |
| Cities             | Restaurant distribution and average ratings |
| Price Range        | Rating and service availability by price    |
| Table Booking      | Availability and rating comparison          |
| Online Delivery    | Availability across price ranges            |
| Customer Votes     | Popular cuisines based on votes             |
| Machine Learning   | Prediction of restaurant aggregate ratings  |

## Repository Contents

```text
restaurant-data-analytics-predictive-modeling/
│
├── Restaurant_Data_Analysis.ipynb
├── Dataset.csv
└── README.md
```

## Conclusion

This project provided practical experience in data preprocessing, exploratory data analysis, feature engineering, visualization, and machine learning. The analysis helped explore the factors associated with restaurant ratings and demonstrated how different regression models can be used to predict restaurant ratings.

M.Sc. Data Science


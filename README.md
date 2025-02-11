# Zomato-Restaurant-Data-Analysis-and-Visulization

****Overview:**

This project explores and analyzes the Zomato restaurant dataset to gain insights into restaurant ratings, cuisines, costs, and geographic distribution. The analysis is performed using Python, and the results are visualized through an interactive dashboard.

**Dataset:**

The dataset used in this project is sourced from Kaggle: [Complete Zomato Dataset]([url](https://www.kaggle.com/code/vahidehdashti/complete-zomato-dataset-eda/input?select=zomato.csv)).

**Files in Repository:**

zomato.csv: Raw dataset containing restaurant details.
zomato.json: JSON format of the dataset for easy parsing.
zomato_eda.ipynb: Jupyter Notebook containing exploratory data analysis (EDA) and visualizations.
zomato_sweetviz_report.html: Auto-generated EDA report using Sweetviz for quick insights.
dashboard.html: Interactive dashboard displaying visualizations of restaurant trends.

**Exploratory Data Analysis (EDA):**

The zomato_eda.ipynb notebook includes:

Data Cleaning and Preprocessing
Analysis of Restaurant Ratings
Cost Analysis of Restaurants
Popular Cuisine Types
Geographic Distribution of Restaurants
Online Service Availability
Key Insights
Distribution of restaurant ratings across different locations
Correlation between cost and restaurant ratings
Most common cuisines in different cities

Geographic clustering of restaurants using latitude and longitude

**Interactive Dashboard:**

The dashboard.html file provides an interactive visualization of restaurant trends using Plotly. Users can upload the zomato.json file to generate:

Rating Distribution
Cost vs. Rating Comparison
Cuisine Popularity
Geographic Distribution of Restaurants
Online Service Availability

How to Use

Open the zomato_eda.ipynb in Jupyter Notebook to explore the analysis.

Open dashboard.html in a web browser and upload zomato.json to view interactive visualizations.

**Dependencies:**

To run the Jupyter Notebook and analysis, install the required Python libraries:

pip install pandas numpy matplotlib seaborn plotly sweetviz

**License:**

This project is open-source and available under the MIT License. <br>
Author: Kintur Shah


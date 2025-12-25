## **Amazon Prime Dataset – Exploratory Data Analysis (EDA)**

**Project Overview**

This project focuses on performing Exploratory Data Analysis (EDA) on the Amazon Prime Video dataset to better understand the platform’s content library. The analysis covers both movies and TV shows, uncovering meaningful trends and patterns related to content types, genres, audience ratings, release timelines, and regional production.

The goal of this project is to transform raw data into actionable insights that help explain how Amazon Prime Video structures its content and adapts to audience preferences.
## 
**Problem Statement**

The Amazon Prime Video dataset provides an opportunity to analyze the platform’s complete catalog and extract valuable insights related to:

* Content Diversity : 
Identifying the most popular genres and categories to understand what type of content dominates the platform and supports strategic content planning.

* Trends Over Time :
Examining how the content library has evolved over the years to reflect changing viewer preferences and industry trends.

* IMDb Ratings and Popularity : 
Analyzing IMDb ratings and popularity metrics to assess audience engagement, highlight high-performing content, and identify areas for improvement.
## 
**Data Wrangling**

Several preprocessing steps were performed to ensure the dataset was clean, consistent, and ready for analysis:

* **Data Loading and Merging**

Two datasets, titles.csv and credits.csv, were loaded and merged using the common identifier id.

* **Handling Missing Values**

  * Rows with missing values in description and imdb_id were removed.

  * Missing values in age_certification were replaced with the most frequently occurring category.

  * Since movies do not have seasons and some records lacked vote or character details, missing values in seasons, imdb_votes, and character were replaced with 0, 0, and 'unknown', respectively.

  * Missing values in imdb_score, tmdb_popularity, and tmdb_score were filled using their respective mean values.
* **Handling Duplicates**
  
Duplicate records were identified and removed to maintain data accuracy.
##
**Data Visualization**

Multiple visualization techniques were used to explore the dataset and extract insights:

* **Univariate Analysis**
Box plots, histograms, and bar plots were used to analyze individual variables such as IMDb scores, runtime, release year, and genre distribution.

* **Bivariate Analysis**
Scatter plots and line plots were used to study relationships between variables, including IMDb votes vs. ratings and trends over time.

* **Multivariate Analysis**
Pair plots and heatmaps were used to visualize correlations and interactions among multiple numerical features.

##
### **Conclusion**

This Exploratory Data Analysis provides a comprehensive view of Amazon Prime Video’s content ecosystem. The findings reveal important patterns in content distribution, genre popularity, audience engagement, and regional contributions. These insights can be valuable for content creators, platform strategists, and viewers to better understand the dynamics of the streaming industry. Further analysis focusing on specific genres, regions, or viewer segments can offer even deeper insights.

Handling Duplicates
Duplicate records were identified and removed to maintain data accuracy.

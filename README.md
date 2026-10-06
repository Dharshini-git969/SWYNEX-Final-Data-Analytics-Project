# 🎬 SWYNEX Final Data Analytics Project
## Movie Ratings, Popularity & Genre Analytics Dashboard
## 📌 Project Overview

This project is the **Final Data Analytics Project** completed as part of my **Data Analytics Internship at SWYNEX Technologies**.

The project analyzes movie ratings, audience engagement, movie popularity, genres, and release-year trends to understand how movies perform from an audience perspective.

The analysis combines data preparation, exploratory data analysis, statistical exploration, and interactive visualization to transform a large movie-rating dataset into meaningful insights.

The final outcome is an **interactive Power BI dashboard** that allows users to explore movie popularity, ratings, genres, and release trends.


# 🎯 Problem Statement

With thousands of movies receiving millions of audience ratings, it can be challenging to understand what makes a movie popular and how popularity relates to audience ratings.

This project aims to answer questions such as:

- Which movies receive the highest number of ratings?
- Does a highly popular movie always have a high average rating?
- How does audience engagement vary across movies?
- How has the number of movie releases changed over time?
- Which genres have the strongest representation?
- How have movie genres evolved across different years?
- What relationship exists between movie ratings and popularity?
- Can movies be categorized based on both recognition and audience engagement?

The dashboard provides an interactive way to explore these questions and identify meaningful patterns in the data.



# 🎯 Project Objectives

The main objectives of this project are:

1. Analyze movie rating patterns.
2. Measure audience engagement using the number of ratings.
3. Identify the most popular movies.
4. Compare average ratings with the number of ratings.
5. Analyze movie releases across different years.
6. Explore genre distribution.
7. Study how genre representation changes over time.
8. Identify patterns between movie recognition and popularity.
9. Present analytical findings through an interactive Power BI dashboard.



# 📊 Dataset Overview

The project uses movie and user-rating data containing information related to:

- Movie IDs
- Movie titles
- Release years
- Genres
- User ratings
- Number of ratings
- User/rater activity

The large volume of rating records makes it possible to study audience engagement and movie popularity at scale.

## Dataset Metrics

The final dashboard displays the following key metrics:

| Metric | Value |
|---|---:|
| 🎬 Total Movies Displayed | **62,423** |
| 👥 Unique Raters | **163K** |
| ⭐ Number of Ratings | **25M** |
| 📊 Average Rating | **3.53** |


# 🧹 Data Preparation

The data preparation stage focused on making the movie-rating data suitable for analysis and visualization.

The preparation process included:

- Reviewing the dataset structure
- Checking data types
- Identifying relevant analytical fields
- Preparing movie and rating information
- Preparing release-year information
- Organizing genre information
- Creating measures required for dashboard analysis
- Validating rating and popularity calculations
- Preparing the data for Power BI visualization

The prepared data was then used for exploratory analysis and dashboard development.


# 🔎 Exploratory Data Analysis

Exploratory analysis was performed to identify patterns and relationships within the movie data.

The analysis focused on:

### ⭐ Rating Analysis

Movie ratings were examined to understand the overall distribution of audience scores and identify differences in rating behavior.

### 👥 Popularity & Audience Engagement

The number of ratings was used as an indicator of audience engagement.

Movies receiving a large number of ratings were analyzed to identify highly recognized and popular titles.

### 🎬 Movie Recognition

Movies were compared using both their average rating and number of ratings.

This helps distinguish between movies that are:

- Highly rated but have relatively fewer ratings
- Highly rated and widely recognized
- Moderately rated with significant audience engagement
- Less recognized due to limited rating evidence

### 📅 Release-Year Analysis

The number of movies represented in the dataset was analyzed across release years to identify long-term changes in movie releases.

### 🎭 Genre Analysis

Movie genres were analyzed to understand their representation and how genre patterns changed over time.



# 📈 Power BI Dashboard

The final interactive dashboard was developed using **Microsoft Power BI**.

The dashboard combines multiple visualizations, KPIs, filters, and analytical categories to provide a comprehensive view of movie performance.

## Dashboard Features

### 1. 🎯 Movie Recognition: Rating vs Popularity

A scatter plot compares:

- **Average Rating**
- **Number of Ratings**

This visualization helps understand the relationship between audience rating and movie popularity.

Movies are categorized into recognition groups such as:

- Hidden Gem
- Highly Recognized
- Low Evidence
- Moderate Recognition
- Popular Hit

This allows movies to be evaluated using both rating quality and audience engagement.


### 2. 🏆 Top 10 Most Popular Movies

The dashboard identifies the movies receiving the highest number of ratings.

The Top 10 visualization includes titles such as:

1. Forrest Gump (1994)
2. The Shawshank Redemption (1994)
3. Pulp Fiction (1994)
4. The Silence of the Lambs (1991)
5. The Matrix (1999)
6. Star Wars: Episode IV – A New Hope
7. Jurassic Park (1993)
8. Schindler's List (1993)
9. Braveheart (1995)
10. Fight Club (1999)

This visualization provides a quick view of movies with strong audience engagement.

### 3. 📅 Movies Released Over Time

A time-series visualization shows the number of movies represented across release years.

The chart highlights the substantial growth in the number of movie titles represented in later periods.

This provides a historical perspective on movie production and dataset representation.


### 4. 🎭 Rating Distribution

The rating distribution visualization provides a genre-level view of rating activity.

It helps compare the contribution of different genres to the overall rating landscape.



### 5. 📊 Comparison of Raters

The dashboard compares audience-related measures across different genres and movie categories.

This helps identify differences in audience engagement and rating activity.


### 6. 🎞️ Titles by Genre Over the Years

A stacked area chart visualizes the representation of different movie genres across release years.

This makes it possible to observe how the relative presence of genres has changed over time.



# 💡 Key Insights

## 1. ⭐ Popularity and Rating Are Different Measures

A movie receiving a large number of ratings is not automatically the movie with the highest average rating.

The comparison between **Average Rating** and **Number of Ratings** shows that audience popularity and rating performance should be evaluated separately.



## 2. 👥 Audience Engagement Varies Significantly

The number of ratings differs substantially between movies.

Some titles receive very high levels of audience engagement, while others have considerably fewer ratings.

This makes the number of ratings a useful measure when evaluating movie recognition.


## 3. 🏆 A Small Group of Movies Receives Very High Engagement

The Top 10 visualization demonstrates that certain well-known movies receive substantially more ratings than many other titles.

This indicates strong audience recognition for established and widely watched movies.


## 4. 🎬 Movie Releases Increase Over Time

The release-year analysis shows a clear long-term increase in the number of movie titles represented in later years.

This indicates significant growth in movie content and availability over time.


## 5. 🎭 Genre Representation Changes Over Time

The genre trend visualization shows that the relative representation of genres is not constant across release years.

Different genres become more or less prominent during different periods.



## 6. 📊 Large-Scale Rating Data Provides Stronger Analytical Context

With approximately **25 million ratings** and **163K unique raters**, the dataset provides a large audience perspective for studying movie engagement.

The scale of the data allows patterns to be observed beyond individual movie examples.


## 7. 💎 High Ratings With Limited Evidence Can Indicate Potential Hidden Gems

Movies with strong average ratings but comparatively fewer ratings may represent titles that are highly appreciated by a smaller audience.

These movies can be distinguished from highly popular movies using the Rating vs Popularity analysis.



# 📌 Key Performance Indicators

The dashboard provides four primary KPIs:

### 🎬 Total Movies
**62,423**

Represents the total number of movie titles displayed in the analysis.

### 👥 Unique Raters
**163K**

Represents the number of unique users contributing ratings.

### ⭐ Total Ratings
**25M**

Represents the total number of movie ratings available for analysis.

### 📊 Average Rating
**3.53**

Represents the overall average movie rating in the analyzed dataset.



# 🛠️ Tools & Technologies

The project uses the following tools and technologies:

- **Python** – Data preparation and analysis
- **Pandas** – Data manipulation
- **NumPy** – Numerical analysis
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Exploratory analysis
- **Microsoft Power BI** – Interactive dashboard development
- **CSV / Excel** – Data handling
- **GitHub** – Project version control and documentation

# 📂 Project Structure

SWYNEX-Final-Data-Analytics-Project/
│
├── README.md
│
├── Data/
│   └── Movie Dataset
│
├── Data_Cleaning/
│   └── Data preparation files
│
├── EDA/
│   └── Exploratory analysis files
│
├── Dashboard/
│   ├── SWYNEX_Task_3_POWER_BI.pbix
│   └── Preview_Task_3.png
│
└── Insights/
    └── Key analytical findings

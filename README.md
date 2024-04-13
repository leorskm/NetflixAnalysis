## Netflix Analysis usind Python

### Project Description

#### Objective
The objective of this Python project is to perform basic statistical analysis and data visualization on a dataset containing information about shows and movies available on Netflix. The analysis aims to provide insights into the distribution of content types, ratings, durations, and trends in content addition over time. The project leverages descriptive statistics, inferential statistics, and linear regression modeling to explore and interpret the data effectively.

#### Data Description
The dataset, `netflix1.csv`, consists of several columns relevant to Netflix's streaming content:

- **show_id**: A unique identifier for each show or movie.
- **type**: The category of the content, either 'Movie' or 'TV Show'.
- **title**: The title of the show or movie.
- **director**: The director(s) of the film or series.
- **country**: The country or countries where the show or movie was produced.
- **date_added**: The date on which the show or movie was added to Netflix.
- **release_year**: The year in which the show or movie was first released.
- **rating**: The age or content rating of the show or movie.
- **duration**: The length of the show or movie, in minutes or seasons.
- **listed_in**: The genres the show or movie is listed under.

This data provides a comprehensive view of the content available on Netflix, allowing for a detailed analysis of trends and patterns in the streaming service's offerings.

#### Tasks Performed

##### 1. **Descriptive Analysis**
- **Data Overview**: Initial exploration of the data types and counts using `data.info()` and summary statistics for numerical columns with `data.describe()`.
- **Content Type Distribution**: Analysis and visualization of the distribution of content types (Movies vs. TV Shows) using `value_counts()` and bar plots to show the prevalence of each type.
- **Rating Distribution**: Visualization of the distribution of content ratings across the dataset to understand viewer discretion trends.
- **Duration Analysis**: Extraction and conversion of duration data from string to numeric format, followed by visualization using box plots to compare durations between movies and TV shows.
- **Top Countries by Content Production**: Identification and visualization of the top 10 content-producing countries, giving insights into Netflix’s global reach and local market focuses.

##### 2. **Inferential Analysis**
- **Average Release Year Comparison**: Calculation of the average release year for movies versus TV shows to identify trends in the age of content by type.
- **Statistical Testing**: Use of a t-test to determine if the differences in release years between movies and TV shows are statistically significant, providing insights into content renewal and addition strategies.

##### 3. **Linear Regression Analysis**
- **Model Preparation**: Encoding of categorical variables and preparation of numerical data for regression analysis.
- **Predictive Modeling**: Development of a linear regression model to predict the release year based on features such as content type and duration.
- **Model Evaluation**: Use of Mean Squared Error (MSE) and R^2 score to evaluate model performance, along with cross-validation to assess the model’s consistency across different subsets of the data.

This structured analysis provides a multi-faceted view of Netflix's catalog, highlighting how content characteristics have evolved over time and offering predictive insights into future content trends based on historical data. Please find the code attached to this repository.

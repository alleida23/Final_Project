# Unveiling Goodreads's "Best Books Ever":
## Data-Driven Analysis and Predictive Modeling of Book Ratings
    * Albert Lleida Estival
    * Iron Hack, April - 2023

This is a data-driven analysis and predictive modeling of book ratings based on the "Best Books Ever" dataset from Goodreads. The goal of this project was to explore the dataset, develop a predictive model for book ratings and build a book recommender system based on clusters.

### Overview
The Goodreads "Best Books Ever" dataset includes information about books' titles, authors, publication years, genres, and ratings, amongst others. 'Genres' and 'awards' unique values were extracted and used as new key predictors.

### Part 0: Data Cleaning and Wrangling
The first part of the project involved cleaning and wrangling the dataset to prepare it for analysis. This included handling missing values, removing duplicates, and converting data types.

### Part 1: Exploratory Data Analysis
In this part, exploratory data analysis (EDA) was performed to gain insights into the dataset. Data visualization techniques were used to analyze the relationships between the different features and the book ratings. Correlation analysis was also performed to identify the features that have the strongest relationships with book ratings.

### Part 2: Predictive Modeling
In the second part of the project, a predictive model for book ratings was developed using a Linear Regression model. The data was split into training and testing sets, and features such as book author, publication year, and genre were used to predict book ratings. The model's performance was evaluated using various error metrics such as R-squared, RMSE, and MAE.

After obtaining initial scores, dimensionality reduction techniques such as PCA and Recursive Feature Elimination (RFE) were applied. Additionally, a Random Forest Regressor model was developed to improve the predictive performance of the model.

### Part 3: Book Recommender
In the third part of the project, a book recommender system was developed based on book clusters. K-means clustering was applied to group books with similar attributes such as author, genre, and publication year. Books were then recommended based on their cluster membership.

### Part 4: Web Scraping
A web scraping script was developed to retrieve data on Pulitzer Prize-winning novels from Wikipedia.

### Technologies Used
Python
Jupyter Notebook
Scikit-learn
Pandas
Matplotlib
Seaborn
BeautifulSoup
Requests

### Repository Structure
This folder contains Jupyter Notebooks with the code for the project, including data cleaning, exploratory data analysis, modeling, and evaluation, as well as the dataset of Pulitzer Prize-winning novels retrieved from Wikipedia.

Original_df: This folder contains the original dataset retrieved from Kaggle.

### Conclusion
This project demonstrated how data-driven techniques can be used to gain insights into book ratings and develop a predictive model. The model developed in this project can be used to predict the ratings of new books based on their features. The book recommender system can help users discover new books based on their preferences. And the addition of the Pulitzer Prize-winning novels & fiction dataset also provides some interesting new information.

### Additional Information
Kaggle dataset source: (https://rb.gy/axmdc)

Wikipedia Pulitzer Prize-winning novels scraping script: (https://en.wikipedia.org/wiki/Pulitzer_Prize_for_Fiction)

Presentation with Canvas: https://rb.gy/mclr1

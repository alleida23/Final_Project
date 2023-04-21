# Final_Project

# Unveiling Goodreads's "Best Books Ever":
## Data-Driven Analysis and Predictive Modeling of Book Ratings

Albert Lleida, April 2023

This is a data-driven analysis and predictive modeling of book ratings based on the "Best Books Ever" dataset from Goodreads. The goal of this project was to explore the dataset, develop a predictive model for book ratings, and build a book recommender system based on clusters.

### Overview

The Goodreads Best Books Ever dataset includes information about books' titles, authors, publication years, genres, and ratings. The dataset also includes information on user reviews, which were not used in this project.

The first part of the project focused on exploring the dataset and developing a predictive model for book ratings. The second part focused on building a book recommender system using clusters.

Part 1: Predictive Modeling
In the first part of the project, a predictive model for book ratings was developed using a Linear Regression model. The data was split into training and testing sets, and features such as book author, publication year, and genre were used to predict book ratings. The model's performance was evaluated using various error metrics such as R-squared, RMSE, and MAE.

After obtaining initial scores, dimensionality reduction techniques such as PCA and Recursive Feature Elimination (RFE) were applied. Additionally, a Random Forest Regressor model was developed to improve the predictive performance of the model.

Part 2: Book Recommender
In the second part of the project, a book recommender system was developed based on book clusters. K-means clustering was applied to group books with similar attributes such as author, genre, and publication year. Books were then recommended based on their cluster membership.

Part 3: Data Collection
To expand the dataset, a web scraping script was developed to retrieve data on Pulitzer Prize-winning novels from Wikipedia. This dataset was then merged with the original dataset to improve the clustering and recommendation processes.

Technologies Used
Python
Jupyter Notebook
Scikit-learn
Pandas
Matplotlib
Seaborn
BeautifulSoup
Requests
Repository Structure
Notebooks: This folder contains Jupyter Notebooks with the code for the project, including data cleaning, exploratory data analysis, modeling, and evaluation.

Data: This folder contains the original dataset retrieved from Kaggle, as well as the dataset of Pulitzer Prize-winning novels retrieved from Wikipedia.

Images: This folder contains images used in the Jupyter Notebooks.

Conclusion
This project demonstrated how data-driven techniques can be used to gain insights into book ratings and develop a predictive model. The model developed in this project can be used to predict the ratings of new books based on their features. The book recommender system can help users discover new books based on their preferences, and the addition of the Pulitzer Prize-winning novels dataset improved the clustering and recommendation processes.

Additional Information
Kaggle dataset source: (https://rb.gy/axmdc)
Wikipedia Pulitzer Prize-winning novels scraping script: (https://en.wikipedia.org/wiki/Pulitzer_Prize_for_Fiction)
Presentation with Canvas: https://rb.gy/mclr1

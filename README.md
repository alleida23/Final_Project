# Final_Project

# Unveiling Goodreads's "Best Books Ever":
## Data-Driven Analysis and Predictive Modeling of Book Ratings

Albert Lleida, April 2023

This is a data-driven analysis and predictive modeling of book ratings based on the "Best Books Ever" dataset from Goodreads. The goal of this project was to explore the dataset, develop a predictive model for book ratings, and build a book recommender system based on clusters.

Overview
The Goodreads Best Books Ever dataset includes information about books' titles, authors, publication years, genres, and ratings. The dataset also includes information on user reviews, which were not used in this project.

The first part of the project focused on exploring the dataset and developing a predictive model for book ratings. The second part focused on building a book recommender system using clusters.

Methodology
Data Retrieval
The data was retrieved from the "Best Books Ever" dataset by Goodreads, which can be found on Kaggle here.

Exploratory Data Analysis
The dataset was explored using Python and various libraries such as Pandas, NumPy, Seaborn, and Matplotlib. The exploratory data analysis included cleaning the data, visualizing the data, and identifying patterns and trends in the data.

Predictive Modeling
A predictive model for book ratings was developed using a Linear Regression model. The data was split into training and testing sets, and features such as book author, publication year, and genre were used to predict book ratings. The model's performance was evaluated using various error metrics such as R-squared, RMSE, and MAE.

Book Recommender System
A book recommender system was built using KMeans clustering. The data was clustered based on book features such as genre and publication year. A user can input a book title, and the system recommends books from the same cluster as the input book.

File Descriptions
The project files are organized as follows:

data: folder containing the dataset used in this project.
books.ipynb: Jupyter notebook containing the code for data cleaning, exploratory data analysis, predictive modeling, and book recommender system.
book_recommender.py: Python script containing the code for the book recommender system.
wikipedia_scraper.py: Python script for web scraping Pulitzer Prize winners of fiction and saving them to a CSV file.
Technologies Used
Python
Jupyter Notebook
Scikit-learn
Pandas
NumPy
Matplotlib
Seaborn
How to Use
Download the project files.
Install the required libraries listed in the requirements.txt file.
Open the books.ipynb notebook in Jupyter Notebook and run the code cells to reproduce the analysis and models.
Use the book_recommender.py script to get book recommendations based on a given book title. Run the script and input a book title when prompted.
Use the wikipedia_scraper.py script to scrape Pulitzer Prize winners of fiction from Wikipedia and save them to a CSV file.
Conclusion
This project successfully developed a predictive model for book ratings and a book recommender system based on clusters. The book recommender system can be used to provide personalized book recommendations to users based on their preferences.

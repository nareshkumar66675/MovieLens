# Weekend Movie Trip

It is a Data Clustering Project.


# What it Does?

  - It recommends movies based on the User Rating, Genres and Tags
  - To build a movie Recommendation system
# Datset Used
- MovieLens : https://grouplens.org/datasets/movielens/
- ###### It contains 4 Data Files.


        Ratings - Contains Rating from multiple user for each movie
        Tags - Contains user comments/tags for each movie
        Movie - Contains Movie name
        Links - Links to Imdb Site for each movie


# Data Clustering
- We are Clustering Datasets using **K-means** clustering

# Feature Engineering
- **Genres**: There were around 20 genres. Each movie is associated with multiple genres (seperated by |)
--Row Data is transformed into New Columns - all genre types. Values are either 0 or 1.
- **Tags**: User tags/comments are available only for few ratings. Since it a text column we have to convert into numerical for clustering. So, we use **tfidf vectorization** to compute new columns based on the tags.


# Analysis
- Data has been clustered in to 20 Clusters. Since there were 20 Genres
- Below Graph Shows the Popularity of Genres - No of Moives in each genres

![Genre Popularity](https://raw.githubusercontent.com/nareshkumar66675/MovieLens/master/reports/GenresPopularity.png "Genre Popularity")

- Below Scatter plot shows the 20 clusters vs Centroids

 ![Scatter Plot](https://raw.githubusercontent.com/nareshkumar66675/MovieLens/master/reports/Scatter-Centroids.png " Scatter Plot")

# Project Struture

##### Src
- MovieLens.py - python file exported from Jupyter
##### Notebooks
- MovieLens.ipynb - Jupyter notebook
##### Data
- External - MovieLens Data
##### Reports
- Plot - Clusters vs Movies
- Genre Popularity


  

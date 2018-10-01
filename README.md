# Weekend Movie Trip

It is a Data Clustering Project.


# What it Does?

  - It recommends movies based on the User Rating, Genres and Tags
  - To build a movie Recommendation system
# Datset Used
- MovieLens : https://grouplens.org/datasets/movielens/
-- It contains 4 Data Files.
-- **Ratings** - Contains Ratimg from multiple user for each movie
-- **Tags** - Contains user comments/tags for each movie
-- **Movie** - Contains Movie name
-- **Links** - Links to Imdb Site for each movie


# Data Classification
- We are classifying Player Line using 4 different classification models.
- ##### Models
        1) Random Forest
        2) Support Vector Machine
        3) Naive Byes
        4) Logistics Regression
- To classify text, we need to convert into numerical forms. So, the player line has been converted to a **tfidf vector**
- This vector is then used to train the model.
# Analysis
- Data has been split into two sets - Train and Test. Using default methodology.
- Below graph shows the Play vs No of Players
![Play vs No of Players](https://raw.githubusercontent.com/nareshkumar66675/Shakespeare/master/reports/PlayVSPlayers.png "Play vs No of Players")
- ##### Accuracy
    --Accuracy for each model is evaluated.
    -- Logistic Regression accuracy rate was higher than the other models.

| Models | Accuracy |
|------------------------|----------|
| SVM | 0.043564 |
| **Logistic Regression** | **0.046845** |
| Naive Byes | 0.032881 |
| Random Forest Classifier | 0.021660 |

- Accuracy Comparison of all the models
- ![Accuracy Comparison](https://raw.githubusercontent.com/nareshkumar66675/Shakespeare/master/reports/ModelComparison.png "Accuracy Comparison")

# Project Struture

##### Src
- Shakespeare.py - python file exported from Jupyter
##### Notebooks
- Shakespeare.ipynb - Jupyter notebook
##### Data
- External - Shakespeare Data
##### Reports
- Plot - Plays vs Player Count and Accuracy Comparison


  

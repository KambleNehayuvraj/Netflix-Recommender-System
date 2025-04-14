#Building And Deploying A Netflix Recommender System
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

We use web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
#Running Flask Tests
To run a Flask deployment tests, run the following command
  python main.py
#Deployment
Prepare your dataset:
Data Extraction
    1. Exploratory Data Analysis(EDA)
    2. Feature Engineering
    3. Model Building and Tuning
    4. Building Flask API
    5. Pushing code to Github
#Demo

![image](https://github.com/user-attachments/assets/f6b8c475-952d-4add-bf71-b09014c086df)


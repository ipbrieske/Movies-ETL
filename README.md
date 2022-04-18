# Movies-ETL

The purpose of this repository is to build a database of movie information for further analysis. The database has been constructed from three sources:
    - A webscrape of Wikipedia movies (wikipedia-movies.json)
    - A Kaggle dataset of movies (movies_metadata.csv)
    - MovieLens ratings for thousands of movies (ratings.csv)

A merged table called "Movies" between wikipedia-movies and movies_metadata and the full ratings table called "Ratings" have been stored in a PostgreSQL database. The Movies table can be used to analyze budgets, box office, release dates, runtimes, and cross reference all information against the 25 million+ ratings from MovieLens. 
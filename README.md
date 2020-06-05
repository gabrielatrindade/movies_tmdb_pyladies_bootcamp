# The Movies Database - TMDB
*Python Bootcamp Data Analysis for Beginners - Capstone project*

## Introduction
We decided to examine the **TMDB 5000 Movie Dataset** for the final project to analyse it through the different production companies, bugdet, revenue, popularity and so on. <br>

This data set was provided by Kaggle through the link: <br>
[https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv) <br>

There you can find almost 5000 movies observations with the following files and columns: <br>
- Files and them columns(1): <br>
    1. **tmdb_5000_credits.csv**:  movies and credits card datatsets. <br>
        columns: **movie_id**, **title**, cast, crew <br>
    2. **tmdb_5000_movies.csv**: Movie credits data. <br>
        columns: **budget**, **genres**, homepage, **id**, keywords, **original_language**, original_title, overview,
        **popularity**, **production_companies**, **production_countries**, **release_date**, **revenue**, **runtime**,
        **spoken_languages**, status, tagline, title, **vote_average**, **vote_count**

    (1) The columns kept for analysis are in bold. The normal ones (unused columns) have been removed from the kaggle
    dataset.

## Questions
* Is there some correlation between: budget, popularity, revenue, vote_average and vote_count?
* Which movies have the highest vote_average? Is the vote_count significant for these movies?
* Which movies people voted the most? Does them vote_average good? Is there some correlation?
* Which movie have the most budget? Which are them production_companies? What was the revenue generated?
* Is there some correlation between the budget and profit? Is profit related to any variable?
* Which movie has the most popularity? Which are them spoken_languages? And the genres?
* Which production_companies have the most movies? And the highest revenue?
* ~~Which movies had the most budget and which cast started in it?~~
  
## Libraries used
    pandas
    json
    seaborn
    matplotlib.pyplot
    numpy

## Challenges
- Data Cleaning: Handle columns in json format

## Team
- @gabrielatrindade
- @kayen88

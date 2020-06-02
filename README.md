# movies_tmdb_pyladies_bootcamp

## TMDB 5000 Movie Dataset
Subset from the real dataset. Some columns was droped.
[https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

- Background
What can we say about the success of a movie before it is released? Are there certain companies (Pixar?) that have found a consistent formula? Given that major films costing over $100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?
This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.

- Data Source Transfer Summary
We (Kaggle) have removed the original version of this dataset per a [DMCA](https://en.wikipedia.org/wiki/Digital_Millennium_Copyright_Act) takedown request from IMDB. In order to minimize the impact, we're replacing it with a similar set of films and data fields from [The Movie Database (TMDb)](https://www.kaggle.com/tmdb/themoviedb.org) in accordance with [their terms of use](https://www.themoviedb.org/documentation/api/terms-of-use). The bad news is that kernels built on the old dataset will most likely no longer work.

- Files and columns(1):
    1. **tmdb_5000_credits.csv**:  movies and credits card datatsets. 
    columns: **movie_id**, **title**
    2. **tmdb_5000_movies.csv**: Movie credits data.
    columns: **budget**, **genres(2)**, **id**, **original_language**, **popularity**, **production_companies**, **production_countries**, **release_date**, **revenue**, **runtime**, **spoken_languages(2)**, **vote_average**, **vote_count**

    (1) It's a subset of the real dataset. Some columns were droped.
    (2) it needs cleaning

- Questions:
  * Which movies have the highest vote_average?
  * Which movies people voted the most?
  * Which movie have the most budget?
  * Which production_companies have the most movies?
  * Which movie has the most popularity?
  * Which movies had the most budget and which cast started in it?

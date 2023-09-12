# Movie-Correlation-Python-Project

# Introduction
This Project performed data-analysis on the Movie Industry Data from Kaggle (https://www.kaggle.com/datasets/danielgrijalvas/movies) using Python to find what variables affects movie's revenue.

In this project, I wonder if there is correlation within the data between the gross revenue of a film and any other aspect(including genre, director, released time, and so on); the initial hypothesis is that gross revenue and budget will have a positive correlation.

# Dataset


The dataset contains 6820 movies in total (220 movies per year, 1986-2016). Each movie has the following attributes:

- budget: the budget of a movie. Some movies don't have this, so it appears as 0

- company: the production company

- country: country of origin

- director: the director

- genre: main genre of the movie.

- gross: revenue of the movie

- name: name of the movie

- rating: rating of the movie (R, PG, etc.)

- released: release date (YYYY-MM-DD)

- runtime: duration of the movie

- score: IMDb user rating

- votes: number of user votes

- star: main actor/actress

- writer: writer of the movie

- year: year of release

The data was scraped from IMDb(https://www.imdb.com/list/ls031674317/) using Python.


# Analysis Procedure

Python libraries: Pandas, Numpy, Seaborn, and Matplotlib

Data pre-processing: 
  - missing value check
  - split the column with weird form('June 13, 1980 (United States)' into 'June 13, 1980' and 'United States')
  - converted the data type of some variables(‘released’, 'buget', 'gross', and so on)
  - de-duplicate
  - check the outlier




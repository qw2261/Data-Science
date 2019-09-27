# DataScience
## MECE E4520 Data Science for Mechanical System
Homework ans Projects

In this Readme.m, we explain the code in the file 'MECEE4520_Homework 3.ipynb'.

In this file, we have used bs4 package which is a scraping package which help developer directly scrape the data in the html file. To achieve our scraping, we first determined what data we want. Here we selected a movie website, called [IMDB](www.imdb.com), which includes a larger amount of features of movies. Our interest is to analyze some problem about movies, such as relationship between any features and box office.

Target determined, we then build a pipeline which can scrape the information of all movies in a page. Then we extended the functions to scrape movies for more than 100 web pages in 2018 and remove those movies without metascore, boxoffice or certificate as a data cleaning method. Then we transform the data into a .csv file for storage.

After the data pipeline design and cleaning, we analyzed the appropriate database schema for the data set. Then, we reloaded the data set to do some analysis on it.

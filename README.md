# Exploratory Data Analysis project. Movies.

![Nice_picture](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/IMG/Index.jpg?raw=true)

## Project Overview

For this project, I use exploratory data analysis of data movies databases to generate insights for a business stakeholder and find three business ideas.

### Business Problem

Microsoft seems all the big companies are creating original video content, and they want to get in on the fun. So they have decided to create a new movie studio, but they don't know anything about producing movies. So you are charged with exploring what types of films are doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Stakeholder

Microsoft

### The Data

##### 1) In the folder `Data` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
Database containing data scraped from Box Office Mojo website tracks box-office revenue in a systematic, algorithmic way.
a) bom.movie_gross.csv 
Type of Information: Revenue data

Film name
Studio
Domestic gross revenue
Foreign gross revenue
Year of production

* [IMDB](https://www.imdb.com/)
Databases containing data scraped from IMDB website. The largest website related to movies.
a) imdb.name.basics.csv -
Type of Information: Names of directing staff and their best known films

PersonID
Name
Profession
Well known filmID

b) imdb.title.akas.csv 
Type of Information: Regions of film destribution and local film names.

FilmID
Region
Film name on local language
Original film name

c) imdb.title.principals.csv
Type of Information: Information about film directors and writers

FilmID
DirectorsID
WritersID

d) imdb.title.basics.csv
Type of Information: Information about start date, runtime and genres

FilmID
Primary film name
Original film name
Start date
Runtime
Genres

e) File imdb.title.ratings.csv
Type of Information: Film raiting, IMDB version

FilmID
Average rating
Number of voites

* [TheMovieDB](https://www.themoviedb.org/)
The Movie Database (TMDB) is a community built movie and TV database.

a) tmdb.movies.csv Type of Information: Information about film production date, name and raiting basd on TMDB

Film name
Release date
Average rating
Number of voites

* [The Numbers](https://www.the-numbers.com/
The Numbers is a film industry data website that tracks box office revenue in a systematic, algorithmic way 

a) tn.movie_budgets.csv Type of Information: Information about film production date, budget and revenue

Film name
Release date
Production Budget
Local gross revenue
International gross revenue
The Movie Database (TMDB)



##### In the folder `Output` are output images:

./Output/Market_estimation.png - market estimation of Box office

./Output/Studios_box.png - Histogram of box offices of 6 major studios-competitors

./Output/Studios_box_75th.png - Histogram of box offices of 6 major studios-competitors 75th percentile

./Output/Cost-rev_scatter.png - Scatterplot of correlation between worldwide box office and production cost

./Output/Cost-rev_scatter_cathegories.png - Scatterplot of correlation between worldwide box office and production cost with films divided into four major categories

./Output/Ganres_nofilter.png - Average annual number of films in different genres without filters. This graph shows how much redundant data we have.

./Output/Distribution_closer_no_filter.png  - Average annual number of films in different genres without any filters and dropped three major categories. This graph shows how much redundant data we have.

./Output/Average_number_with3filters.png - Average annual number of films in different genres after applying three filters to reduce the amount of data and improve the quality.

./Output/Most_popular_ganres.png - most popular Genres, their mean box office, and the number of films. X-axis genres, Y - rating (by voting on IMDB.com), size - number of movies, hue - average box office

./Output/Ganres_boxOffice.png   - barplot representing median worldwide box office for each genre.

./Output/Ganres_boxplot.png - boxplot for each genre worldwide box office. Needed for in-depth research

./Output/Director_raitings.png - Rating of movies of the most famous directors 


##### In the folder `IMG` are images used in Jupiter notebook.


## Key business recommendations:

1) BUDGET
The planned budget for the film should be: 20+ mln USD:

The Majority of films are within 20-100mln USD budget.
Some films should have 100+ mln USD budget.
Films with higher budgets tend to earn higher box office.

2) GENRES
The studio should focus on genres: 
- adventure,
- animation,
- sci-fi
Films in these genres have a higher rating and the highest box office with the median value of 200M +
- Action movies can be considered as an option for low-budget films. 

3) DIRECTORS
There are a variety of top-performing directors to choose from. The list is provided with this report.
It is possible to choose a director based on genre and availability. 

## Presentation

the non - technical presentation is available at the root of this folder:
./Presentation.pdf

## Jupyter Notebook

Jupyter Notebook is available at the root of this folder:
./student.ipynb


## Visualizations:

![Market Estimation](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Market_estimation.png)
![Major Studios film box office histogram](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Studios_box.png)
![Average number of films per genre](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Average_number_with3filters.png)
![Most popular genres](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Most_popular_ganres.png)
![Mean box office per genre](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Ganres_boxOffice.png)
![Poxplot box office per genre(advance research)](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Ganres_boxplot.png)
![Popular directors](https://github.com/314ka4y/dsc-phase-1-project-v2-3/blob/master/Output/Director_raitings.png)


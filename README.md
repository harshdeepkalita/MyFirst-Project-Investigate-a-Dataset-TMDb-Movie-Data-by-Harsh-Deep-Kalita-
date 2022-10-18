> <h1>Welcome to My Investigate a Dataset project!</h1>


# Project: Investigate a Dataset (TMDb Movie Data)
> <h2>By Harsh Deep Kalita</h2>

## Table of Contents
<ul>
<li>Introduction</li>
<li>Data Wrangling</li>
<li>Exploratory Data Analysis</li>
<li>Conclusions</li>
</ul>

<a id='intro'></a>
## Introduction

### TMDb Data Set :
- This data set contains information about 10,000 movies collected from <b>The Movie Database (TMDb)</b>,including user ratings and revenue.
- This data set contains : rows = 10866 , columns = 21
- I am going to showcase my data cleaning, wrangling and visualisation (Exploratory Data Analysis) skills using <b>pandas,numpy, matplotlib and seaborn libraries</b> in this project.

<a id='wrangling'></a>
## Data Wrangling

> I am going to do the following steps:
- Load the data set into a DataFrame.
- Find the general Properties of the Data Set.
- Find the duplicate rows and drop them.
- Find the null values or odd characters present in specific columns and, either drop them or fill them with appropriate values(eg: mean).
- Find the attributes which are not useful for extracting insights from our dataset and drop them.

<a id='eda'></a>
## Exploratory Data Analysis

>Questions:
- Which genre was popular the for majority of the years (1960-2015)?
- Which year has the highest release of movies?
- Who are the Top 10 Directors with highest number of movies (From 1960 - 2015) ?
- What are the Top 10 and Bottom 10 Movies according to the ratings of the viewers?
- Which Movies have the highest profit and loss?
- Which length movies are most liked by the audiences according to popularity?
- What are the Average Budget Of Movies From Year To Year?
- Do movies with higher budget have higher profit?
- What kinds of properties are associated with movies that have high revenues?
- Which month released highest number of movies in all years ?
- Which Month Made The Highest Average Revenue?

<a id='conclusions'></a>
## Conclusions
- "Thriller" was the most popular genre for majority of the years (1960 to 2015)
- Highest Release of Movies were made in the year 2014.
- Woody Allan has directed the highest number of movies (42 movies).
- Number 1 Movie according to the ratings of the viewers is Pink Floyd:Pulse.
- Least rated movie by the viewers is Manos: The Hands of Fate(1.5 rating).
- Highest profit movie is "Avatar", following Star Wars: The Force Awakens and then Titanic.
- Lowest profit movie is "The Warrior's Way".
- The Audience  prefer movies with long duration (100 to 200 mins or 2.5 to 2.8hrs).
- Higher budget movies have higher average profit compared to lower budget movies.
- Revenue is strongly related to the Budget.
- Highest number of releases happen during the month of september.
- Movies released in the month of May and June have the highest revenue compared to the other months.

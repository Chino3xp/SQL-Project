# SQL-Project
# Exploring covid-19 Data using SQL

This is a brief summary of the project

# INTRODUCTION

In this project, Covid-19 dataset was gotten from ourworldindata.org and i explored the data using Sqlite to analyze and gather insights to be used for visualization in
tableau.


## ABOUT THE DATA

After downloading the data, i removed some columns that are not relevant in my analysis using MS Excel and also divided the data into two, namely, Covid_deaths and Covid_vaccinations
after this, i uploaded them in a sqlite database

## INSIGHTS FROM THE ANALYSIS

The first query was written to find the death percentage in Nigeria which shows that as of 29th of October 2022, Nigeria has a death percentage of 1.18%

The second query was to look at total cases vs population to get the Percentage of population that got covid in Nigeria, which showed 0.12% as of 29th of October 2022.

Countries with the highest infection rate compared to the population was checked and it showed Cryprus as the highest infection rate compared to the population and 
Faeroe islands comes in second.

Countries with the highest death count per population showed the United States as top country with the highest death count per population.

Using Joins, the Total population vs vaccinations was querried from the two tables Covid_deaths and Covid_vaccinations.

Then using rolling count to find out new vaccines recieved.  

A temp table was created in other to divide the rolling count by population as it cannot be divided because its a new column that was just created. This is to get the result in percentage.

Finally, i created a view for later visualizations.

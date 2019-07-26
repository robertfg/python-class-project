# New York Mets Improvement Project
Code Louisville Python Project July 2019

## Background
The `New York Mets` are a National League baseball team.  They are perenially bad and I am a frustrated fan looking for ways to improve the club.

## Question
Is there one area where the `New York Mets` can look to improve the most?  Where would the `Mets` get the most bang for their buck?

## Overview

### Data Source
Baseball Databank is a compilation of historical baseball data in a convenient, tidy format, distributed under Open Data terms, which I found on `kaggle.com`.  Most of the data in the Databank is provided by Chadwick Baseball Bureau (http://www.chadwick-bureau.com).

From this data, I used a subset of the files:

* Batting.csv
* Fielding.csv
* FieldingOFsplit.csv
* People.csv
* Pitching.csv
* Teams.csv

### Analysis
The `Mets` starting pitching was well above league average; however, their relief pitching was below average.  They didn't hit well either, but if they could only improve their bullpen they would be a much better club.

## Glossary
Baseball-specific terminology:
* Earned Run Average:  the number of earned runs a pitcher allows per nine innings, with earned runs being any runs that score without the aid of an error or a passed ball.
* Batting Average: a player's hits divided by his total at-bats for a number between zero (shown as 0.000) and one (1.000). 
* Run Differential: the difference between the number of runs a team scores versus the number of runs the team gives up.

## Requirements, Dependencies, Steps

### Requirements
To run this project, you will need to have Jupyter Notebook installed.  Do this by downloading and installing Anaconda Navigator (https://www.anaconda.com/), which provides a suite of software for use with data analytics.

### Dependencies
The following data libraries were used:
* matplotlib
* pandas
* numpy
* sqlite3
* os (included, but not used)

### Steps
To run this project:
1.  Clone this repo.
2.  Run jupyter notebook.
3.  Change folders to the python-class-project project folder.
4.  Open the python-class-project.ipynb file.
5.  Run all cells.


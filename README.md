

### Date created
7th May 2023

# Project Title
US Bike-share Data analysis

## Description
This project is an analysis of bike share data for the cities of Chicago, New York, and Washington. The program prompts the user to select a city and specify a time frame for analysis. Statistical analysis is then performed on the data and results are presented to the user.

## How to Run the Program
To run the program, open a command prompt or terminal and navigate to the directory where the bikeshare.py file is located. Then, type python bikeshare.py to launch the program.

The program will prompt you with the following questions:

- "Would you like to see data for Chicago, New York, or Washington?"
- "Would you like to filter the data by month, day, or not at all?"
- (If the user chooses month) "Which month - January, February, March, April, May, or June?"
- (If the user chooses day) "Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?"
- The user's responses to these questions will determine the city and timeframe for analysis.

## Data Analysis
After the user has selected a city and time frame, the program will load the corresponding data and perform statistical analysis on it. The following information will be displayed:

* Total trip count
* Trip duration statistics (mean, median, mode)
* Popular stations and routes
* User type breakdown (subscribers vs. customers)
* Gender breakdown (if available)
* Birth year statistics (if available)
* The user will then be prompted to choose whether they would like to see raw data, and whether they would like * to restart the program or exit.

### Files used
1. For New York - [https://citibikenyc.com/system-data]
2. For Chicago -  [https://divvybikes.com/system-data]
3. For Washington - [https://capitalbikeshare.com/system-data]

### Dependencies
This program requires Python 3.x and the following Python libraries:
1. pandas
2. time
3. datetime

### Acknowledgments
This project was completed as part of the Udacity Programming for Data Science Nanodegree program. Thanks to Udacity for providing the bike share data and project guidance.


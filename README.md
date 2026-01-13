SQL to Python Integration: Lahman Baseball Database Analysis

 Project Overview
This project was completed during Week 9 at Nashville Software School and focuses on integrating SQL with Python to build more flexible, repeatable data analysis workflows.

The primary objective was to translate previously written SQL queries into Python code using SQLAlchemy and Pandas, reinforcing Python fundamentals through familiar SQL concepts. The project uses the Lahman Baseball Database, a well-known relational dataset commonly used for analytical and database exercises.

Rather than treating SQL and Python as separate tools, this project demonstrates how they complement each other in real-world data analytics.


 Tools & Technologies
SQL
Python
SQLAlchemy
Pandas
Jupyter Notebook
Relational Databases


Key Learning Outcomes
Translating SQL logic (SELECT, JOIN, GROUP BY, filtering) into Python workflows
Connecting databases to Python using SQLAlchemy
Using Pandas to manipulate, analyze, and visualize query results
Understanding when SQL is optimal for querying vs when Python adds analytical flexibility
Thinking in terms of end-to-end data pipelines, not isolated queries

This project strengthened my ability to move from one-off SQL queries to reusable, scalable analytical code.


Dataset
Lahman Baseball Database
Compiled and maintained by Sean Lahman
Includes comprehensive historical baseball data: players, teams, salaries, attendance, awards, and more
A full data dictionary is included with the dataset


Analytical Questions Addressed

Core SQL-to-Python Translations
What range of years does the baseball games data cover?
Who is the shortest player in the database, how many games did they play, and which team did they play for?
Which players attended Vanderbilt University, and how much total salary did they earn in the major leagues?
Which Vanderbilt player earned the most during their MLB career?

Position-Based & Performance Analysis
Grouped players into:Outfield,Infield,Battery (Pitchers & Catchers)
Calculated total putouts by group for the 2016 season
League-Wide Trends
Calculated average strikeouts per game by decade since 1920
Calculated average home runs per game by decade
Identified long-term trends in offensive and pitching performance

Player & Team Performance
Identified the most successful base stealer in 2016 (minimum 20 attempts)
Analyzed:
Highest wins by a team that did not win the World Series
Lowest wins by a team that did win the World Series
Explained anomalies caused by shortened seasons
Measured how often the team with the most wins also won the World Series (1970–2016)

Attendance & Popularity
Identified top 5 and bottom 5 parks by average attendance per game in 2016
Analyzed attendance trends in relation to:Team wins , Playoff appearances,World Series victories

Awards & Career Milestones
Managers who won TSN Manager of the Year in both the AL and NL
Players who hit their career-high home run total in 2016 , given:At least 10 years in the league , At least one home run in 2016

📈 Open-Ended Analysis
Correlation between team salary and number of wins (2000–present)
Relationship between wins and attendance
Impact of World Series and playoff appearances on future attendance
Investigation into whether left-handed pitchers : Are statistically rarer , Are more effective , Win Cy Young Awards more frequently , Are more likely to enter the Hall of Fame

🎯 Why This Project Matters
This repository demonstrates my ability to:
Bridge SQL and Python in real analytical workflows
Work with relational databases programmatically
Ask meaningful business and performance questions of data
Translate raw data into structured insights

🚀 Target Role
Data Analyst / Junior Data Analyst
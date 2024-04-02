Project 3 (Data Visualization)
Group Members:
Avani Patel
Clarke Allan
Matt Owens
Banesa Casillas
Fantasy Footbal Player Performance Dashboard
If you've been playing fantasy football for some time, you've likely experienced the frustration of having a seemingly unbeatable team early in the season, only to see it falter in the playoffs.

With so many uncertainties, it's challenging to pinpoint the reasons behind a player's sudden decline in production when it matters most. Could there be underlying trends in the data that could help anticipate future performance?

To help address these questions and make more informed decisions, we’ve developed the following dashboard to allow you to see a player's historic weekly performance.

Player Performance Dashboard:
Run the app.py in the Flaskfolder to access the dashboard.

image

Home Screen: image

Player Display: image

Top Chart Displays the players cumulitive points over the last 5 years of data by week
Bottom Left Displays the breakdown of how they earned fantasy points
Bottom Right Displays the most recent 5 performances
How to use the Player Performance Dashboard via Flask App:
To access the Player Performance Dashboard, navigate to the Flask app located in the Flask folder and run the app.py file.

Navigating the Home Page:

Once you've accessed the Flask app, you'll land on the Home Page. Choose the position you want to analyze.

Player Page:

After selecting a position, you'll have the option to use the player search feature. This feature enables you to search for specific players and view their performance trends over time. At any point, you can return to the Home Page by clicking "Home"

Git Hub Directory:
Flask App:
app.py : main file used to run flask app
templates : HTML templates displayed on Player Page
static : Data and backgoround image
Data Wrangling:
Web Scraping : Code used for web scraping using BeautifulSoup
Transforming : Code used for manipulating data before storage, years and weeks per player combined, column titles editied, data types and spacing edited
Data Design:
Table Schema: SQL database schema
Queries: SQL Queries
Images: ERD document and screenshots of SQL Queries
SQLAlchemy : Code used to pull data from database and transform to usable format with visualizations
Ethics:
Fantasy football data is derived from NFL game statistics, rooted in real-world player performance. However, it's crucial to acknowledge the presence of selection bias within this dataset. While fantasy points are calculated based on standardized NFL game statistics, the interpretation and application of these numbers can vary across different fantasy football leagues. The dashboard's metrics are tailored to reflect a Points Per Reception (PPR) scoring style, offering insights aligned with this specific scoring system. It's important to recognize that users' league settings may differ, impacting the relevance and applicability of the visualization to their particular scoring rules.

Furthermore, the dataset encompasses player performance data from the past five years, providing an overview of recent trends. It's worth noting that some players may have more extensive data histories than others, potentially influencing the depth of analysis for certain individuals.

Inclusive of all available data points, even instances where players have scored zero points are included. However, the reasons behind these zero scores are not explicitly displayed within the dashboard.

Data Source: FootballDB
Image: Freepik Realistic american footbal stadium
https://www.freepik.com/free-vector/realistic-american-football-stadium_11733976.htm#query=american%20football%20field&position=0&from_view=keyword&track=ais&uuid=2e6983e7-c456-443a-8021-03bd72de6675

Libraries:
Flask
SQLAlchemy
Pandas
Splinter
BeautifulSoup
Selenium
Plotly
Chart.JS
Technologies:
SQL
PostgresSQL
Python
Jupyter Notebook
ChatGPT
JavaScript
CSS -HTML
About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Contributors
4
@AiMO-MO-MO
AiMO-MO-MO Matt Owens
@clarkeallan931
clarkeallan931
@blanc88
blanc88 BLC
@avani-16
avani-16 Avani
Languages
Jupyter Notebook
99.5%
 
Other
0.5%
Suggested workflows
Based on your tech stack
Python Package using Anaconda logo
Python Package using Anaconda
Create and test a Python package on multiple Python versions using Anaconda for package management.
Publish Python Package logo
Publish Python Package
Publish a Python Package to PyPI on release.
Webpack logo
Webpack
Build a NodeJS project with npm and webpack.
More workflows
Footer
© 2024 GitHub, Inc.

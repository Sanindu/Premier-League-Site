# Football Teams Performance Report Application

This application displays football team data from a database in a table, allowing users to generate reports on selected teams. The reports include team information, a pie chart of match statistics, and a bar chart comparing multiple teams. The application is secured with a login system to ensure that only authorized users can access its features.

### Login
![](https://github.com/Sanindu/Premier-League-Site/blob/main/login.gif)

### Performance comparison using Chart.js
![](https://github.com/Sanindu/Premier-League-Site/blob/main/view_chart.gif)

### Add New Record
![](https://github.com/Sanindu/Premier-League-Site/blob/main/new_rec.gif)

### Edit Record
![](https://github.com/Sanindu/Premier-League-Site/blob/main/edit_rec.gif)

Features <br />
JSON Schema <br />
JSON schema (Leagueschema.json) to validate League.json. <br />
Ensured realistic data types and restrictions for each data element. <br />

JavaScript and HTML <br />

League.html: Displays the Premier League Teams Table. <br />
Topscorers.html: Displays the Premier League Top Scorers table. <br />
Automatically update data at realistic intervals using setTimeout. <br />

Ensured no delay in loading data when the page first opened - AJAX. <br />
Formated HTML professionally using CSS. <br />

Included icons for each reported game/match, reflecting wins (green icons) and losses (blue icons) in the last six games. <br />
Used JavaScript to calculate total points based on wins (3 points) and draws (1 point). <br />

# Task 2: Generate Teams Performance Report
Display Teams Data <br />
Display all football teams data stored in the database in an HTML table. <br />
Order the table in ascending order based on current points. <br />
Each row contains a checkbox for selecting the team for the report. <br />
The first cell in the table header contains a checkbox to select/deselect all teams.

# Generate Report

On clicking the "Generate Report" button, a report page is displayed with:
A table showing selected football teams' information.
A pie chart using Chart.js, showing percentages of matches played (wins, losses, draws, and remaining games).
A bar chart comparing selected teams if more than one team is selected.

# Secure Application
A login page allows authorized users to enter their username and password to access the application features.

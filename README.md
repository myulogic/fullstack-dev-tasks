# Javascript Developer Tasks
Please create the following two applications –
## Task 1
Create a Node.js script to take local file path of the provided sample Excel file (like "C:\Users\GKalyan\Documents\sample.xlsx") as argument and do the following -

1. Parse/extract data from the two worksheets in the Excel file

2. Load parsed/extracted data (like Sheet name, Column header, the number values, etc.,) into any NoSQL DB (preferably MongoDB) such that the result needed in the second task is possible

3. Handle error scenarios like file missing in the path, Parser exceptions (non-numeric characters in number columns), etc., with an appropriate error response with proper logging in a log file

## Task 2
Create a reasonably styled MERN stack application to connect to NoSQL DB from first task and display the contents of the Excel file in a data grid (one data grid per Excel worksheet)

## Bonus Points

 - Deploy the MERN application to Heroku/MongoDB Atlas
 - Secure the MERN application on Heroku using an authentication mechanism (preferably token-based)
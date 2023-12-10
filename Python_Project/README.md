## Python Project
Create Website and fetch data with help of Sqlit3

## Table Content:
1 : Project file

2 : Database file

3 : Companies.csv file

4 : database.db file

5 : Website file

6 : README.md file


## Project file(Project.ipynb)
This file contains Data collection & Data Processing information.

In this file the data is sraped from Real time website .

The Website link : https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue'

In this file we have to perform data scraping and data cleaning , we use BeautifulSoup for parsing HTML and XML documents. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.
 
After cleaning data according to proper rows and columns the data is converted into csv file and the name of csv file is Companies.csv


## Companies.csv file

The csv file contains data in forms of excel sheet for use in Database.

## Database file(Database.ipynb)

In this file we have to perform fuction with the help of Sqlite3 , which is used to convert csv file into database, after this we gave a name to our database file (database.db).

## database.db file

For this file if you want to check your data is converted into database or not you can direclty go on google and search for SQLite Viewer Web App and open your folder where your database file is get stored.

## website file(website.ipynb)

For this we have to create website and fetch the data and display on screen, for this we use flask and other python functions.
For making website we use HTML and CSS for styling

In this we create one folder named as templates , in which we have our file stucture for website 

For website main page the Home.html file is there and for database we have index.html file .

# SEC-Database-

Notes of Interest: 
-	This code assumes that Jupyter Notebook and MySQL is already installed 
-	The user might have to change conditions of the MySQL local server to connect to their database 
o	This code assumes that the local server is created with the conditions of the username : root  and password : password
-	Note that the Functions file is changed to Functions – Copy. This is because this is a copy of the original file contains a personal API Key. In order to recreate this file the user must change the name of the file back to its original name “Functions” as well as creating their own API Key from the TD Developers website. 
-	The users are expected to run the SEC Database File prior to any other files

Limitations of the Code and Bugs: 
-	With this current data set there are some bugs that have been patched or planning soon. For easier maintenance in GitHub this bugs and issues will being fixed and uploaded as a lump sum in the future when the next version of this code in completed. 
o	Issues that are addressed are as followed.
	Cash amount of Dividends and Dividend Per Share require further data cleaning. 
	Bug with CAGR function yield a ‘nan’ value when present value or future value is negative. 

Features expected to be added in the future versions: 
-	Multiple Treads to speed up the time it takes to collect the data
-	A overall score out of 100 to each company evaluating the companies health based on fundamental and forecasting data
-	Interacting with Google Trend Rest API to find trend in popular google searches in a time frame and a group of companies
-	Adding Sub-Industry groups and Sector to Company Information data table in MySQL

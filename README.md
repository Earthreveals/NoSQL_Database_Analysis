# nsql-challenge
OVERVIEW
Evaluate the ratings data of a food magazine, Eat Safe Love, to help journalists and food critics in the UK Food Standards Agency evaluate various establishments and provides
them with a guidance of good hygiene rating. In this NoSQL assignment, a database is used and Jupyter Notebook is setup. 

REQUIRED LIBRARIES
PyMongo
Pretty Print
Pandas

INSTALLATION
Database and Jupyter Notebook Set Up
Use NoSQL_setup_starter.ipynb for this section of the challenge.
Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. 
Create an instance of the Mongo Client.
Confirm that you created the database and loaded the data properly:
List the databases you have in MongoDB. Confirm that uk_food is listed.
List the collection(s) in the database to ensure that establishments is there.
Find and display one document in the establishments collection using find_one and display with pprint.
Assign the establishments collection to a variable to prepare the collection for use

USAGE
To run scripts in python, we will use libraries above to analyze data using python. Scripts are run in Anaconda prompt by opening the terminal and navigating to the directory where the script is located. 
Python scripts can be ran using the command python script_name.py. PyMongo and Pretty Print libraries along with Pandas will be utilized. 

DATA
Data is provided in the establishments.json file. The database is parsed into uk_food and collection establishments. 

ANALYSIS
Eat Safe, Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid.
Use NoSQL_analysis_starter.ipynb for this section of the challenge.
From the data, the following questions will be answered.
Which establishments have a hygiene score equal to 20?
Which establishments in London have a RatingValue greater than or equal to 4?
What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
RESULTS

CONTRIBUTER
Nick Nath

LICENSE
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.
Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

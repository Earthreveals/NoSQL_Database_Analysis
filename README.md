# NoSQL Database Analysis

This repository contains a project that evaluates the ratings data of a food magazine, Eat Safe Love, to help journalists and food critics in the UK Food Standards Agency evaluate various establishments and provides them with guidance on good hygiene ratings. In this NoSQL assignment, a database is used and Jupyter Notebook is setup.

## Overview

The objective of this project is to use NoSQL databases to store and analyze data from the UK Food Standards Agency. The data includes ratings for various establishments, and the goal is to provide insights into hygiene standards across different locations.

## Required Libraries

- PyMongo
- Pretty Print
- Pandas

## Installation

### Database and Jupyter Notebook Setup

1. **Set Up NoSQL Database:**
   - Use `NoSQL_setup_starter.ipynb` for this section of the challenge.
   - Import the data provided in the `establishments.json` file from your terminal.
   - Name the database `uk_food` and the collection `establishments`.
   - Create an instance of the Mongo Client.
   - Confirm that you created the database and loaded the data properly:
     - List the databases you have in MongoDB.
     - Confirm that `uk_food` is listed.
     - List the collection(s) in the database to ensure that `establishments` is there.
     - Find and display one document in the `establishments` collection using `find_one` and display using `pprint`.
     - Assign the `establishments` collection to a variable to prepare the collection for use.

2. **Run Scripts in Python:**
   - Use libraries to analyze data using Python.
   - Scripts are run in Anaconda prompt by opening the terminal and navigating to the directory where the script is located.
   - Run the script using the command `python script_name.py`.
   - Utilize PyMongo and Pretty Print libraries along with Pandas.

## Data

The data is provided in the `establishments.json` file. The database is parsed into `uk_food` and the collection `establishments`.

## Analysis

Eat Safe Love has specific questions they want you to answer, which will help them find the locations they wish to visit and avoid. Use `NoSQL_analysis_starter.ipynb` for this section of the challenge. From the data, the following questions will be answered:
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0?
- Sort the results from highest to lowest, and print out the top ten local authority areas.

## Files in the Repository

- **NoSQL_analysis_starter.ipynb**: Jupyter notebook for the NoSQL analysis.
- **NoSQL_setup_starter.ipynb**: Jupyter notebook for setting up the NoSQL database.
- **establishments.json**: Data file containing information about various establishments.

## Project Structure
├── README.md
├── NoSQL_analysis_starter.ipynb
├── NoSQL_setup_starter.ipynb
└── establishments.json

## Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/NoSQL_Database_Analysis.git
   cd NoSQL_Database_Analysis
2. **Install the required dependencies**
   pip install pymongo pandas
3. **Run the Jupyter Notebooks**
  jupyter notebook NoSQL_setup_starter.ipynb
  jupyter notebook NoSQL_analysis_starter.ipynb

## Results
The results of the analysis will provide insights into the hygiene standards of various establishments, helping Eat Safe Love make informed decisions about where to visit and which places to avoid.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
UK Food Standards Agency for providing the data.
Contributors and study group members who provided guidance and support throughout the development of this project.


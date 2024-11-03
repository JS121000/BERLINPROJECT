# GitHub Berlin User & Repository Analysis
* This project uses the GitHub API to scrape information about users in Berlin with over 200 followers and their repositories.
* One surprising insight was the prevalence of certain programming languages, suggesting dominant developer preferences within Berlin's tech community.
* Developers looking to build their presence may want to focus on these languages or engage more actively to grow their networks.


#Project Overview
This repository contains data scraped from the GitHub API, specifically for users in Berlin with more than 200 followers and up to 500 of their recent public repositories. The goal was to gather insights about Berlin's GitHub community, highlighting key attributes, trends, and areas for potential developer growth.

#Data Files
The dataset includes two CSV files:

users.csv: Contains user data, including GitHub login, name, company, location, bio, and follower/following counts.
repositories.csv: Contains data on each user's public repositories, with details such as repository name, language, stars, and license information.
Setup Instructions
Clone this repository.
Make sure you have Python installed along with requests and pandas libraries.
Run the provided script github_data_scraper.py to fetch data from the GitHub API.
Code Structure
The main script that interacts with the GitHub API, fetches data, and writes it to CSV files.
Data Cleaning: Company names are standardized, and extraneous whitespace is removed. Email fields are left empty where data is unavailable.
Usage
To analyze the data, run additional analysis scripts included or use the raw data in the CSV files for custom insights.

Additional Insights
Beyond the main findings, additional trends in user activity, follower ratios, and repository language distribution are included in the analysis folder.

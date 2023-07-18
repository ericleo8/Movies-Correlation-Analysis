# Movies Correlation Analysis
Welcome to the repository for the Movie Correlation Data Analysis project! 
In this project, I have conducted a comprehensive analysis of movies dataset using Python for data exploration, data cleaning, and data analysis, and Tableau for data visualization. 
This repository serves as a resource for exploring the project's code, data, and findings.

### About the dataset
There are 6820 movies in the dataset (220 movies per year, 1986-2016). Each movie has the following attributes:
- budget: the budget of a movie. Some movies don't have this, so it appears as 0
- company: the production company
- country: country of origin
- director: the director
- genre: main genre of the movie.
- gross: revenue of the movie
- name: name of the movie
- rating: rating of the movie (R, PG, etc.)
- released: release date (YYYY-MM-DD)
- runtime: duration of the movie
- score: IMDb user rating
- votes: number of user votes
- star: main actor/actress
- writer: writer of the movie
- year: year of release

### Acknowledgements
This data was scraped from IMDb.

### Project Overview

### Tools & Technique Used
In this analysis, I leveraged the power of Python for data exploration, data cleaning, and data analysis. Additionally, I utilized Tableau for data visualization. Tableau is a platform to create visually appealing and interactive visualizations that help uncover patterns, trends, and key insights from the data. The visualizations provide a clear and intuitive representation of the analysis findings.

### Project Goals
The primary goal of this repository is to explore and analyze the Movies Dataset to gain insights into the industry. Through data analysis and visualization techniques, we aim to answer various questions such as:

- How many total movies based on genres were produced?
- How many total movies have been produced year after year by genre?
- What movies are successful based on their Return On Investment?
- What movies have the highest budget?
- How many movies each country produced?
- What companies made the most of movies?
- Who are the most popular and voted Directors?

### Data Exploration
The data exploration phase involved examining the dataset to understand its structure, contents, and any potential issues or inconsistencies. I used Python to perform initial data exploration tasks, such as:

- Reviewing the dimensions and structure of the dataset.
- Identifying missing values or inconsistencies.
- Investigating relationships between variables.

### Data Cleaning
I performed several tasks to clean and preprocess the data, including:

- Handling missing values by imputation or removal, depending on the specific context.
- Removing duplicate records to avoid redundancy.
- Standardizing formats and correcting inconsistencies in variables, such as released column.
- Transforming variables as needed to align with the analysis objectives.

### Data Visualization 
The visualizations provide a clear representation of the key insights and make it easier to understand and interpret the data.

See the dashboard, click [here](https://public.tableau.com/app/profile/eric.leonardo/viz/MoviesDashboard_16892344049690/MoviesDashboard).

***

## Key Findings 

Through the analysis of Glassdoor's data science job postings dataset, several key findings were uncovered. We can see that:

- Comedy films are the most made films from 1980 until 2020
- There are 3 movies that are most often made every year namely comedy, action and drama.
- A Polish Vampire in Burbank is the most successful movie based on its ROI: 26,166% with budget only 3,000 and made over 78,000,000 on gross
- Avengers: Endgame is the most top highest budget with $356,000,000. If you ever watch this one, it has amazing CGI effect so I have no doubt about it why it has to be the highest one.
- United States produced most of the movies with 5475 movies
- Universal Pictures made the most 

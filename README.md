📊 Netflix Data Analysis with Pandas
This project explores and analyzes a real-world Netflix dataset using Python and Pandas. The goal was to extract meaningful insights about the type of content Netflix offers — including trends in releases, most common genres, durations, ratings, and countries producing the content.

📁 Dataset
Source: Kaggle Netflix Dataset (or specify your source)

Rows: ~8800

Columns: 12

Includes information like:

Title

Type (Movie/TV Show)

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Genre (listed_in)

Description

📌 Objectives
Clean and preprocess the dataset

Handle missing values and data types

Perform grouping and aggregation

Derive insights through EDA (Exploratory Data Analysis)

Prepare the dataset for potential visualization or modeling

🧹 Data Cleaning Steps
Checked and handled missing values in director, cast, country, date_added, etc.

Converted date_added to datetime format

Separated duration into numerical part and unit (for example: 90 min, 2 Seasons)

Removed duplicates and standardized text data

📊 Analysis & Insights
Most common types of content: Movies vs TV Shows

Most popular genres and their frequency

Top contributing countries to Netflix’s content

Distribution of content over the years

Average duration of movies per country

Most frequent ratings (e.g. TV-MA, PG, R, etc.)

📦 Tools & Libraries Used
Python 3.x

Pandas

NumPy

Matplotlib / Seaborn (if you used visualizations)

📁 Project Structure
kotlin
Copy
Edit
📂 netflix-data-analysis/
├── netflix_data.csv
├── Netflix_Analysis.ipynb
├── cleaned_netflix_data.csv
└── README.md

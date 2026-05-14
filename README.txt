# Video Game Market Analysis Dashboard (Excel)

## Project Overview
This project analyzes a large dataset of video games to identify trends in publishers, developers, genres, release years, and review sentiment. The analysis was completed entirely in Microsoft Excel using data cleaning techniques, formulas, Pivot Tables, Pivot Charts, and an interactive dashboard.

## Objectives
- Clean and prepare raw data imported from Kaggle
- Analyze the top publishers and developers by number of games
- Identify the most common genres
- Examine review sentiment and rating distributions
- Explore release trends over time
- Build an interactive dashboard with slicers

## Dataset
- Source: Kaggle
- Records: 6,000 base game entries
- Fields Used:
  - ID
  - Title
  - Publisher
  - Developer
  - Release Date
  - Genre
  - Review
  - Rating (custom classification)

## Tools Used
- Microsoft Excel
- Excel Tables
- IFERROR, IFS, RIGHT, COUNT, UNIQUE
- Conditional Formatting
- Pivot Tables
- Pivot Charts
- Slicers

## Data Cleaning Steps
- Replaced missing text values with `N/A`
- Removed duplicate records
- Fixed encoding issues from CSV import
- Removed unwanted `#` characters before `N/A`
- Created a `Rating` column using `IFS()` based on review sentiment
- Created a `Year` column using `RIGHT()` to extract release years
- Applied custom Conditional Formatting to `Review` and `Rating`

## Dashboard Components
- Top Publishers by Number of Games
- Top Developers by Number of Games
- Top Genres
- Genre vs Reviews
- Games Released by Year
- Rating Distribution
- Interactive slicers for Genre, Review, Rating, and Year

## Key Insights
- Ubisoft and Electronic Arts are among the publishers with the highest number of games.
- Action and Adventure are among the most common genres.
- Most games have positive user reviews.
- The number of released games increased significantly in recent years.

## Dashboard Preview
![Dashboard](dashboard.png)

## Files Included
- `Video_Game_Analysis_Portfolio.xlsx`
- `dashboard.png`
- `README.md`
- `video_games.csv`

## Skills Demonstrated
- Data Cleaning
- Data Transformation
- Excel Formulas
- Exploratory Data Analysis
- Pivot Tables and Pivot Charts
- Dashboard Design
- Data Storytelling

## Author
Created by Viktor Gavrailov
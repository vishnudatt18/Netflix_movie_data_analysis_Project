
# Netflix Movie Data Analysis

This repository contains a comprehensive exploratory data analysis (EDA) of a Netflix movie dataset using Python and popular data science libraries. The project demonstrates data preprocessing, cleaning, transformation, and visualization techniques applied to real-world movie data from Netflix.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Analysis Workflow](#analysis-workflow)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

***

## Project Overview

The goal of this analysis is to derive insights from Netflix movie data through preprocessing, categorical transformations, and visual exploration. The notebook demonstrates how to handle raw data, extract meaningful features, and answer questions such as "Which genres are most frequent?" and "Which genres have the highest votes?".

## Dataset

The dataset consists of **9827 movies** and 9 features, including:
- ReleaseDate
- Title
- Overview
- Popularity
- VoteCount
- VoteAverage
- OriginalLanguage
- Genre
- PosterUrl

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/netflix-movie-data-analysis.git
   cd netflix-movie-data-analysis
   ```

2. Open the Jupyter Notebook:
   - Run in Jupyter or Google Colab: **Netflix_movie_data_analysis.ipynb**

3. Install the requirements:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```

## Analysis Workflow

- **Data Import & Inspection:**  
  Loading the CSV data and performing an initial inspection (shape, missing values, duplicates, column data types).

- **Data Cleaning & Preprocessing:**
   - Converting date columns and extracting the year.
   - Dropping irrelevant columns (`Overview`, `OriginalLanguage`, `PosterUrl`).
   - Handling outliers in numerical columns.
   - Splitting and categorizing genres.
   - Creating categorical labels for `VoteAverage` (e.g., popular, average, belowavg, notpopular).

- **Data Transformation:**
   - Exploding genre lists for per-genre analysis.
   - Casting categories for efficient memory use.

- **Exploratory Data Analysis:**
   - Visualizing most frequent genres.
   - Identifying genres with the highest number of votes.
   - Aggregating and analyzing popularity and rating trends.

## Key Findings

- The **most common movie genres** and those receiving the **highest audience votes** are highlighted.
- Ratings have been categorized for deeper insight into movie popularity distribution.
- Genre-based and year-based patterns in ratings and popularity.

## Visualizations

The analysis includes:
- Bar plots of genre frequency
- Genre vote comparisons
- Distribution histograms
- Yearly trends

All visualizations are built with **matplotlib** and **seaborn**.

## Dependencies

- **numpy**
- **pandas**
- **matplotlib**
- **seaborn**

## Contributing

Feel free to fork, contribute, or suggest improvements via pull request or issue.





[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85659815/c429fcc1-6a0a-49a0-95bb-0d69f8d244eb/Netflix_movie_data_analysis.ipynb)

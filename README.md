# Movie_Ratings_Data_Processing
# Movie Ratings Analytics

## Overview
This project focuses on processing and analyzing movie and user rating datasets using Python and Pandas.

The notebook demonstrates essential data science workflows including data loading, preprocessing, DataFrame merging, filtering, aggregation, feature engineering, and exploratory data analysis (EDA).

The objective is to extract meaningful insights from movie ratings and user behavior while applying professional data manipulation techniques.

---

## Dataset

The project uses two CSV files:

### `movies.csv`
Contains movie-related information:
- `movieId`: unique movie identifier
- `title`: movie title
- `genres`: movie genres

### `ratings.csv`
Contains user ratings:
- `userId`: unique user identifier
- `movieId`: movie identifier
- `rating`: user rating (0.5 to 5)
- `timestamp`: UNIX timestamp of the rating

---

## Main Tasks Performed

- Loading and inspecting datasets
- Merging relational datasets using Pandas
- Filtering and querying movie ratings
- Calculating rating statistics
- Identifying top-rated movies
- Feature extraction from movie titles
- Extracting release years using regular expressions
- Genre filtering and analysis
- UNIX timestamp conversion to readable dates

---

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Regular Expressions (re)

---

## Project Structure

```text
movie-ratings-analytics/
│
├── data/
│   ├── movies.csv
│   └── ratings.csv
│
├── notebooks/
│   └── movie_ratings_analysis.ipynb
│
├── images/
│
├── README.md
└── requirements.txt

# Spotify Data Cleaning & Analysis

This project involves cleaning and analyzing a Spotify dataset using Python and pandas. It enables users to interactively explore top songs by genre or artist, check for non-explicit versions of songs, and visualize popular music trends.

---

## Dataset

* The dataset is loaded from `kaggle`
* It includes attributes like:

  * `artists`, `album_name`, `track_name`
  * `track_genre`, `popularity`, `explicit`

---

## Features

### Data Cleaning

* Removes:

  * Missing (`NaN`) values
  * Duplicate records

###  Data Exploration

* **Top 10 Songs by Genre**
  Prompts the user to input a music genre and returns the top 10 most popular songs in that genre.

* **Top 10 Songs by Artist**
  User inputs the name of an artist and receives the artist's top 10 songs by popularity.

* **Non-Explicit Version Check**
  Checks if a song is available in a non-explicit (clean) version.

###  Visualizations

* **Top 5 Most Popular Genres**
  Bar chart showing the five most common genres in the dataset.

* **Top 5 Artists**
  Based on frequency of appearance in the dataset.

---

##  Technologies Used

* **Python** (Pandas, NumPy, Matplotlib)
* Google Colab / Jupyter Notebook

---

##  Getting Started

1. Upload the `dataset.csv` file to your Colab or working directory.
2. Run the notebook `spotifydatacleaning.ipynb`.
3. Follow on-screen prompts for genre, artist, or song search.
4. View visualizations for insights on popular genres and artists.

---

##  Note

* Artist names in the dataset may be delimited by `;`. The script splits these for accurate counting.
* Popularity is assumed to be a numerical score where higher is better.

---



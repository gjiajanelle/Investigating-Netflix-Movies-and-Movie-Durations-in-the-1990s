# 🍿 Investigating Netflix Movies and Movie Durations in the 1990s

An exploratory data analysis (EDA) project analyzing Netflix movie durations, genres, and release trends, with a special focus on the cinema of the 1990s using Python, pandas, and matplotlib 🎬.

---

## 📌 Overview

Has movie length changed over time? This project explores Netflix's movie catalog to investigate historical patterns in film runtimes, focusing on identifying the most frequent movie duration in the 1990s and analyzing short-form action films from that decade ⏱️.

### 🎯 Key Objectives
* 🎥 Filter and isolate movie records from Netflix's overall catalog.
* 📅 Analyze movie release trends and runtime distributions across the 1990s (1990–1999).
* ⏱️ Determine the most frequent movie duration (`duration`) in the 1990s.
* 💥 Count the number of short action movies (`short_movie_count`) released in the 1990s with runtimes under 90 minutes.

---

## 📁 Project Structure

```text
├── project-investigating-netflix-movies.ipynb      # Main Jupyter Notebook containing data analysis and visualizations
├── netflix_data.csv    # Dataset containing Netflix movies and TV shows
├── redpopcorn.jpg      # Asset / cover visual
└── README.md           # Project documentation
```

---

## 🗃️ Dataset Description

The analysis uses `netflix_data.csv`, which includes metadata on Netflix titles:

| Column Name | Type | Description |
| :--- | :--- | :--- |
| `show_id` | string | Unique identifier for each title |
| `type` | string | Identifier: `Movie` or `TV Show` |
| `title` | string | Title of the movie or show |
| `director` | string | Director(s) of the content |
| `cast` | string | Main cast members |
| `country` | string | Country/countries of production |
| `date_added` | string | Date added to Netflix |
| `release_year` | integer | Original release year |
| `duration` | integer | Duration in minutes (for movies) or seasons (for shows) |
| `description` | string | Brief synopsis / plot summary |
| `genre` | string | Primary genre / category (e.g., Action, Comedies, Dramas) |

---

## 🔍 Key Findings

* 🎞️ **1990s Runtime Distribution:** Visualized the distribution of film runtimes throughout the 1990s decade, revealing a strong concentration around standard feature-length runtimes.
* 🎯 **Most Frequent Duration:** Identified the single most common movie duration in minutes for films released between 1990 and 1999.
* 🥊 **Short Action Films:** Quantified short action movies released in the 1990s with a duration under 90 minutes.

---

## 🚀 How to Run

### 1. ⚙️ Prerequisites
Ensure Python 3.8+ is installed along with the required libraries:
* `pandas`
* `matplotlib`
* `jupyter`

### 2. 💻 Installation & Setup
Clone the repository and install dependencies:
```bash
git clone [https://github.com/gjiajanelle/Investigating-Netflix-Movies-and-Movie-Durations-in-the-1990s.git](https://github.com/gjiajanelle/Investigating-Netflix-Movies-and-Movie-Durations-in-the-1990s.git)
cd Investigating-Netflix-Movies-and-Movie-Durations-in-the-1990s
pip install pandas matplotlib jupyter
```

### 3. ▶️ Running the Analysis
Launch the Jupyter Notebook environment to inspect the analysis and execute the cells:
```bash
jupyter notebook project-investigating-netflix-movies.ipynb
```

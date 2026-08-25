# 🍿 Investigating Netflix Movies and Movie Durations in the 1990s

An exploratory data analysis (EDA) project analyzing Netflix movie durations, genres, and release trends, with a special focus on the cinema of the 1990s using Python, pandas, and matplotlib 🎬[cite: 3].

---

## 📌 Overview

Has movie length changed over time? This project explores Netflix's movie catalog to investigate historical patterns in film runtimes, focusing on identifying the most frequent movie duration in the 1990s and analyzing short-form action films from that decade ⏱️[cite: 3].

### 🎯 Key Objectives
* 🎥 Filter and isolate movie records from Netflix's overall catalog[cite: 3].
* 📅 Analyze movie release trends and runtime distributions across the 1990s (1990–1999)[cite: 3].
* ⏱️ Determine the most frequent movie duration (`duration`) in the 1990s[cite: 3].
* 💥 Count the number of short action movies (`short_movie_count`) released in the 1990s with runtimes under 90 minutes[cite: 3].

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

The analysis uses `netflix_data.csv`, which includes metadata on Netflix titles[cite: 3]:

| Column Name | Type | Description |
| :--- | :--- | :--- |
| `show_id` | string | Unique identifier for each title[cite: 3] |
| `type` | string | Identifier: `Movie` or `TV Show`[cite: 3] |
| `title` | string | Title of the movie or show[cite: 3] |
| `director` | string | Director(s) of the content[cite: 3] |
| `cast` | string | Main cast members[cite: 3] |
| `country` | string | Country/countries of production[cite: 3] |
| `date_added` | string | Date added to Netflix[cite: 3] |
| `release_year` | integer | Original release year[cite: 3] |
| `duration` | integer | Duration in minutes (for movies) or seasons (for shows)[cite: 3] |
| `description` | string | Brief synopsis / plot summary[cite: 3] |
| `genre` | string | Primary genre / category (e.g., Action, Comedies, Dramas)[cite: 3] |

---

## 🔍 Key Findings

* 🎞️ **1990s Runtime Distribution:** Visualized the distribution of film runtimes throughout the 1990s decade, revealing a strong concentration around standard feature-length runtimes[cite: 3].
* 🎯 **Most Frequent Duration:** Identified the single most common movie duration in minutes for films released between 1990 and 1999[cite: 3].
* 🥊 **Short Action Films:** Quantified short action movies released in the 1990s with a duration under 90 minutes[cite: 3].

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

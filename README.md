# 🎬 Netflix Data Analysis

Exploratory Data Analysis (EDA) of a Netflix movies dataset to uncover trends in genres, popularity, ratings, and release patterns.

---

## 📌 Project Overview

This project performs end-to-end exploratory data analysis on a Netflix movies dataset sourced from TMDB (The Movie Database). The goal is to extract meaningful insights about content trends, audience preferences, and popularity distributions using Python and interactive visualizations.

---

## 📂 Project Structure

```
Netflix-Data-Analysis/
│
├── Netflix_Data_Analysis.ipynb   # Main Jupyter Notebook with full EDA
├── NetflixData.csv               # Dataset used for analysis
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## 📊 Dataset

**File:** `NetflixData.csv`

| Column | Description |
|---|---|
| `Release_Date` | Date the movie was released |
| `Title` | Movie title |
| `Overview` | Short description of the movie |
| `Popularity` | Popularity score (from TMDB) |
| `Vote_Count` | Number of user votes |
| `Vote_Average` | Average user rating (out of 10) |
| `Original_Language` | Language the movie was originally made in |
| `Genre` | One or more genres associated with the movie |
| `Poster_Url` | URL to the movie's poster image |

---

## 🔍 Key Analysis Performed

- **Data Loading & Preview** – Loading the CSV and inspecting initial rows
- **Data Cleaning** – Handling missing values and formatting columns
- **Genre Analysis** – Most frequent genres on Netflix
- **Popularity Analysis** – Distribution and top movies by popularity score
- **Ratings Analysis** – Vote average distribution across movies
- **Release Trend** – Number of movie releases over the years
- **Language Distribution** – Breakdown of movies by original language
- **Correlation Analysis** – Relationships between popularity, votes, and ratings

---

## 💡 Key Insights

- **Drama** is the most frequently occurring genre in the dataset.
- **Adventure** movies show the highest average popularity among all genres.
- **Action** and **Science Fiction** also receive strong audience interest.
- Movie releases increased significantly **post-2000**, reflecting the growth of streaming platforms.
- The popularity distribution is **highly skewed** — most movies are average, with only a few becoming blockbuster hits.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – Data manipulation and analysis
- **Plotly Express** – Interactive visualizations
- **Jupyter Notebook** – Development environment

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the notebook
```bash
jupyter notebook Netflix_Data_Analysis.ipynb
```

> **Note:** If you're running on Google Colab, upload `NetflixData.csv` to `/content/` and run all cells directly.

---

## 📧 Contact

Feel free to reach out or raise an issue if you have suggestions or questions!

# 🎬 Movies Dataset – Data Cleaning and Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on cleaning, processing, and performing Exploratory Data Analysis (EDA) on a movies dataset using Python.

The main objective is to analyze movie information, identify patterns, explore relationships between different variables, and understand how factors such as genre, production country, director, budget, revenue, and popularity influence movie performance.

## 🎯 Project Objectives

- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Convert columns into appropriate data types.
- Extract useful information from JSON-formatted columns.
- Analyze movie ratings, popularity, budget, revenue, and profit.
- Identify relationships between numerical variables.
- Explore movie trends based on genres, countries, directors, and keywords.
- Visualize insights using charts and heatmaps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development environment |

## 📂 Dataset Information

**Dataset:** The Movies Dataset

**Source:** Kaggle

https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

The project uses the following datasets:

- `movies_metadata.csv` – Movie information, budget, revenue, ratings, popularity, and release dates.
- `keywords.csv` – Keywords associated with movies.
- `credits.csv` – Movie cast and crew information.

## 🧹 Data Cleaning and Preprocessing

The following preprocessing steps were performed:

1. Removed unnecessary columns that were not required for the analysis.
2. Removed duplicate records.
3. Handled missing and null values.
4. Converted numerical columns into appropriate data types.
5. Converted release dates into datetime format.
6. Extracted release year from release dates.
7. Converted collection information into binary values.
8. Processed JSON-formatted columns such as genres, production companies, production countries, cast, crew, and keywords.
9. Replaced invalid zero values in budget and revenue with missing values.
10. Normalized budget, revenue, and profit values.
11. Calculated weighted movie ratings.
12. Merged metadata, keywords, and credits datasets using movie IDs.

## 📊 Exploratory Data Analysis (EDA)

The project explores the following areas:

### 1. Top Movies Analysis
- Top 10 movies based on weighted ratings.
- Top 10 movies based on popularity.
- Top 10 movies based on profit.

### 2. Numerical Data Analysis
- Correlation between budget and revenue.
- Relationship between revenue and profit.
- Relationship between vote count and revenue.
- Correlation between popularity and other numerical variables.
- Correlation heatmap.

### 3. Genre Analysis
- Movie distribution by genre.
- Average weighted ratings by genre.
- Popularity and vote count by genre.
- Budget and revenue comparison across genres.

### 4. Country Analysis
- Movie production across different countries.
- Average ratings by country.
- Popularity and vote count comparisons.
- Revenue and budget analysis.

### 5. Director Analysis
- Comparison of directors based on movie ratings.
- Director popularity analysis.
- Budget and revenue comparisons.
- Identifying top-performing directors.

### 6. Keyword Analysis
- Analysis of movie keywords.
- Popularity based on keywords.
- Vote count comparisons.
- Budget, revenue, and profit analysis.

### 7. Director and Cast Correlation
- Identification of top directors and actors.
- Analysis of relationships between directors and cast members.

## 🔍 Key Findings

- Movie budget and revenue show a strong positive correlation.
- Revenue and profit have a very strong positive correlation.
- Movies with higher vote counts tend to generate higher revenue.
- Adventure, Fantasy, Animation, Science Fiction, Family, and Action genres show higher average popularity and revenue-related values.
- Movie popularity and ratings vary across directors and production countries.
- Keywords such as "based on novel", "prison", "sex", and "paris" show higher popularity in the analyzed dataset.

## 📁 Project Structure

```text
Movies-Dataset-Analysis/
│
├── movies-dataset-data-cleaning-and-analysis.ipynb
├── README.md
│
└── Datasets link included in jupyternotebook file.
    ├── movies_metadata.csv
    ├── keywords.csv
    └── credits.csv
```

*Note: The dataset files should be downloaded separately from Kaggle.*

## ⚙️ How to Run This Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/Movies-Dataset-Analysis.git
```

**Step 2: Navigate to the project folder**

```bash
cd Movies-Dataset-Analysis
```

**Step 3: Install required libraries**

```bash
pip install pandas numpy matplotlib seaborn kagglehub jupyter
```

**Step 4: Open Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5:** Open `movies-dataset-data-cleaning-and-analysis.ipynb` and execute the cells.

## 🚀 Future Improvements

- Develop an interactive movie analytics dashboard using Power BI.
- Build a movie recommendation system.
- Apply machine learning models to predict movie revenue.
- Perform advanced analysis on movie ratings and popularity.

## 👨‍💻 Author

**Badri Narayana S N**

Information Science and Engineering

**Areas of Interest:** Data Analytics | Python | SQL | Machine Learning | Power BI

---

⭐ If you find this project useful, feel free to explore and star the repository!

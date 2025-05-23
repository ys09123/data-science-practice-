# 📊 Netflix Titles Data Analysis

This project analyzes the **Netflix Titles Dataset**, focusing on data cleaning, preprocessing, and exploratory data analysis (EDA) using Python libraries such as `pandas`, `matplotlib`, and `seaborn`.

## 🗂️ Dataset
The dataset used is `netflix_titles.csv`, which contains information about movies and TV shows available on Netflix. Key columns include:
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`

## 📌 Key Features

### ✅ Data Cleaning
- Handling missing values in `director`, `cast`, `country`, and `rating`
- Dropping records with missing `date_added` or `duration`
- Removing duplicate entries
- Converting data types for `date_added` and `release_year`

### 📊 Exploratory Data Analysis (EDA)
- **Univariate Analysis:**
  - Content type (Movie vs TV Show)
  - Ratings distribution
  - Release year trends
  - Year-wise additions to Netflix
  - Top 10 countries producing content

- **Bivariate Analysis:**
  - Type vs Rating
  - Type vs Year Added
  - Release Year vs Type (stacked histogram)

## 🛠️ Tools & Libraries
- Python
- Google Colab
- pandas
- numpy
- seaborn
- matplotlib

## 📁 File Structure
- `practice.ipynb`: Main Jupyter notebook (uploaded via Colab)
- `netflix_titles.csv`: Dataset file (uploaded by the user)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ys01923/netflix-dataset-analysis.git
   cd data-science-practice

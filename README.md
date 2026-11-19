Netflix Movies and TV Shows - Data Analysis Using Python

An exploratory data analysis (EDA) and feature engineering project on the Netflix Movies and TV Shows dataset using Python. This project walks through the end-to-end data analysis pipeline—from data loading and cleaning to statistical analysis, static/interactive visualizations, and feature engineering.

Dataset

Name: Netflix Movies and TV Shows (netflix_titles.csv)
Source: Kaggle - Netflix Shows Dataset
Size: 8,807 rows and 12 columns (Movies and TV Shows available on Netflix up to 2021)
Project Workflow

Dataset Collection: Defined the problem statement, objectives, and dataset overview.
Python & NumPy Operations: Created arrays and computed descriptive statistics (mean, median, standard deviation, min, max, percentiles) on movie durations and release years.
Pandas Inspection: Checked dataset shape, data types, summary statistics, missing value percentages, and duplicate rows.
Data Cleaning & Preprocessing: Standardized column names, imputed missing values (director, cast, country, date_added, rating, duration), parsed dates and numeric durations, and detected outliers using the IQR method.
Exploratory Data Analysis (EDA): Analyzed content type ratios, top countries, content ratings, yearly additions, and correlations.
Static Visualizations (Matplotlib & Seaborn): Created a 6-plot dashboard including a histogram, bar chart, line chart, scatter plot, box plot, and correlation heatmap.
Interactive Visualizations (Plotly): Built interactive charts for release year distribution, movie duration vs. release year by rating, and top content-producing countries by type.
Feature Engineering: Extracted date/time features (added_year, added_month, added_day_of_week), engineered domain features (content_age_at_addition, genre_count, cast_count, description_word_count), encoded categorical columns, and scaled numerical variables using StandardScaler.
Analysis & Conclusion: Summarized key insights, patterns, recommendations, and dataset limitations.
Key Findings

Catalog Split: The catalog consists of ~70% Movies (6,131) and ~30% TV Shows (2,676).
Movie Runtimes: Average movie length is 99.58 minutes (median 98 minutes), with most falling between 87 and 114 minutes.
Content Growth: Content additions grew rapidly after 2015, with an increasing focus on newly released titles (content_age_at_addition dropping over time).
Regional Trends: The US and India lead in Movie production, whereas South Korea and Japan contribute a higher share of TV Shows.
Target Audience: TV-MA and TV-14 are the most common ratings across the platform.
Tech Stack & Libraries

Python 3
NumPy & Pandas (Data manipulation and numerical analysis)
Matplotlib & Seaborn (Static data visualization)
Plotly (Interactive visualizations)
Scikit-learn (Label encoding and feature scaling)
Jupyter Notebook
How to Run

Clone this repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install the required dependencies:
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
Ensure netflix_titles.csv is in the root directory alongside netflix_titles_dpa_assignment.ipynb.
Launch Jupyter Notebook and open the file:
jupyter notebook netflix_titles_dpa_assignment.ipynb


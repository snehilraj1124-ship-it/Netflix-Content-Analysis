# Netflix Content Analysis — Extended

## 📊 Project Overview

This project is an extended streaming-content analytics project designed to explore how data analytics can be used to understand a large content catalog.

The analysis covers **3,000 synthetic content records** across Movies and TV Shows and examines content type, genre, country, release year, ratings, popularity, views, audience scores, production budgets and award nominations.

> **Important:** This project uses synthetic data created for educational and portfolio purposes. It does not represent Netflix's actual catalog, internal metrics or company statistics.

---

## 🎯 Project Objectives

- Analyze Movies vs TV Shows
- Understand genre distribution
- Analyze country-wise content distribution
- Study release-year trends
- Analyze content ratings
- Compare popularity and viewership
- Study the relationship between views and audience scores
- Compare average views across genres
- Compare audience scores across countries
- Analyze Genre × Content Type relationships
- Generate business-oriented insights

---

## 🗂️ Dataset

The dataset contains **3,000 synthetic content records**.

### Features

| Feature | Description |
|---|---|
| Content_ID | Unique content identifier |
| Title | Synthetic content title |
| Type | Movie or TV Show |
| Genre | Primary content genre |
| Country | Associated country |
| Release_Year | Content release year |
| Rating | Content rating |
| Duration | Movie duration or TV show seasons |
| Popularity_Score | Synthetic popularity score |
| Views_Million | Synthetic views in millions |
| Content_Rating_Score | Synthetic content rating score |
| Production_Budget_Million | Synthetic production budget |
| Award_Nominations | Synthetic award nomination count |
| Audience_Score | Synthetic audience score |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Microsoft Excel
- OpenPyXL
- Exploratory Data Analysis
- Data Visualization
- Business Analytics
- Data Storytelling

---

## 🔍 Analysis Performed

### 1. Content Type Analysis

Compared Movies and TV Shows based on:

- Number of titles
- Average popularity
- Average views
- Average audience score

### 2. Genre Analysis

Analyzed:

- Genre representation
- Average views by genre
- Average audience score
- Content rating patterns

### 3. Country Analysis

Compared countries based on:

- Number of titles
- Average views
- Average audience score

### 4. Release-Year Analysis

Analyzed the distribution of content across release years from **2010 to 2025**.

### 5. Rating Analysis

Examined the distribution of different content ratings and compared audience performance.

### 6. Performance Analysis

Analyzed the relationship between:

- Popularity
- Views
- Audience Score
- Content Rating Score

### 7. Genre × Type Analysis

Used cross-tabulation to understand how different genres are distributed between Movies and TV Shows.

---

## 📈 Visualizations

### Content Distribution by Type

![Content by Type](01_content_by_type.png)

### Content Distribution by Release Year

![Release Year](02_content_by_release_year.png)

### Content Distribution by Genre

![Genre](03_content_by_genre.png)

### Content Distribution by Country

![Country](04_content_by_country.png)

### Views vs Audience Score

![Views vs Audience Score](05_views_vs_audience_score.png)

### Average Views by Genre

![Average Views](06_average_views_by_genre.png)

### Audience Score by Country

![Audience Score](07_audience_score_by_country.png)

---

## 💡 Key Business Insights

1. Content catalogs can be analyzed at multiple levels rather than relying only on total title counts.

2. Genre-level analysis can help identify highly represented and less represented content categories.

3. Country-level analysis provides a framework for understanding geographic content diversity.

4. Release-year analysis can help monitor catalog freshness and content trends.

5. Views and audience scores can be examined together to identify highly engaging content.

6. Comparing Movies and TV Shows provides useful format-level insights.

7. Rating analysis can help understand the composition of the target audience.

---

## 📊 Excel Workbook

The project includes:

`netflix_content_analysis_extended.xlsx`

The workbook contains:

- **Content Data**
- **By Type**
- **By Genre**
- **By Country**
- **By Year**
- **By Rating**
- **Genre × Type**

---

## 📁 Project Structure

```text
netflix-content-analysis/
│
├── netflix_content_dataset_extended.csv
├── netflix_content_analysis_extended.py
├── netflix_content_analysis_extended.xlsx
│
├── 01_content_by_type.png
├── 02_content_by_release_year.png
├── 03_content_by_genre.png
├── 04_content_by_country.png
├── 05_views_vs_audience_score.png
├── 06_average_views_by_genre.png
├── 07_audience_score_by_country.png
│
├── analysis_report.md
└── README.md

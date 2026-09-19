# Netflix_data_analysis
Exploratory Data Analysis of Netflix Movies and TV Shows using Python, Pandas, NumPy, Matplotlib and Seaborn.

# 🎬 Netflix Data Analysis — Exploratory Data Analysis with Python

## 📌 Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** of Netflix Movies and TV Shows using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.

The objective of this project is to understand Netflix's content library through data-driven analysis, identify patterns in movies and TV shows, analyze content growth over time, explore countries and genres, examine ratings and movie durations, and extract meaningful insights from the dataset.

The project follows a complete data analysis workflow:

**Data Collection → Data Understanding → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Statistical Analysis → Visualization → Insights → Conclusion**

The analysis focuses on both basic and advanced EDA techniques that are commonly used in real-world data analyst and data science projects.

---

## 🎯 Project Objectives

The major objectives of this analysis are:

- Understand the structure and characteristics of the Netflix dataset.
- Analyze the distribution of Movies and TV Shows.
- Identify missing values and data-quality issues.
- Clean and transform important columns.
- Analyze how Netflix content has been added over time.
- Compare Movies and TV Shows added across different years.
- Identify countries producing the most Netflix content.
- Analyze the most common genres/categories.
- Understand the distribution of content ratings.
- Analyze movie duration using NumPy and Pandas.
- Analyze the number of seasons in TV Shows.
- Identify frequently appearing directors and actors.
- Compare Movies and TV Shows across countries and genres.
- Analyze monthly patterns in content additions.
- Extract meaningful business and content-level insights.
- Build visualizations that communicate findings clearly.

---

## 📊 Dataset

The dataset used for this project is the **Netflix Titles Dataset**, containing information about Movies and TV Shows available on Netflix.

### Dataset Size

- **Rows:** 8,807
- **Columns:** 12

### Dataset Columns

| Column | Description |
|---|---|
| `show_id` | Unique identifier for each title |
| `type` | Type of content — Movie or TV Show |
| `title` | Name of the movie or TV show |
| `director` | Director of the title |
| `cast` | Main cast members |
| `country` | Country or countries associated with the title |
| `date_added` | Date the title was added to Netflix |
| `release_year` | Original release year |
| `rating` | Content rating |
| `duration` | Movie duration or number of seasons |
| `listed_in` | Genre/category of the title |
| `description` | Short description of the title |

---

# 🛠️ Tools & Technologies

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

### Environment

- Google Colab / Jupyter Notebook

### Skills Demonstrated

- Data Loading
- Data Understanding
- Data Cleaning
- Missing Value Analysis
- Data Transformation
- Feature Engineering
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- GroupBy Analysis
- Filtering
- String Manipulation
- Data Extraction
- Handling Multi-value Columns
- NumPy Statistical Operations
- Business/Content Insights

---

# 📁 Project Structure

```text
Netflix-Data-Analysis/
│
├── README.md
│
├── dataset/
│   └── netflix_titles.csv
│
├── notebook/
│   └── Netflix_Data_Analysis.ipynb
│
└── images/
    ├── movies_vs_tv.png
    ├── content_over_time.png
    ├── movies_tv_over_time.png
    ├── top_countries.png
    ├── top_genres.png
    ├── rating_distribution.png
    ├── movie_duration.png
    └── tv_show_seasons.png
```
# 📈 Important Visualizations

## The major visualizations created in this project include:

- Movies vs TV Shows
- Netflix Content Added Over Time
- Movies vs TV Shows Added Over Time
- Top 10 Countries
- Top 10 Genres
- Rating Distribution
- Release Year Distribution
- Top Directors
- Top Actors
- Movies vs TV Shows by Country
- Movies vs TV Shows by Genre

# 🔍 Key Insights
## Content Composition

Netflix's catalog contains both Movies and TV Shows, with Movies representing a substantial portion of the dataset.

The content-type analysis provides a clear overview of the structure of the Netflix catalog.

## Content Growth

The yearly content-addition analysis shows how Netflix's catalog expanded over different periods.

The comparison between Movies and TV Shows allows us to understand whether content additions were driven more by Movies or TV Shows during different years.

## Geographic Distribution

The country analysis shows that Netflix's catalog is geographically diverse, with certain countries appearing much more frequently than others.

The split-and-explode technique was necessary because many titles are associated with multiple countries.

## Genre Distribution

Netflix contains a wide range of genres.

The genre analysis identifies the categories appearing most frequently and allows comparison between Movie and TV Show content.

## Ratings

The rating distribution provides insight into the types of audiences targeted by Netflix content and shows which content classifications occur most frequently.

## Movie Duration

Movie duration analysis shows the distribution of runtimes across Netflix Movies.

Using NumPy makes it possible to calculate:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Percentiles
- TV Show Seasons

TV Shows were analyzed separately from Movies because their duration column represents seasons rather than minutes.

This separation prevents incorrect statistical calculations.

## Data Quality

Several columns contain missing information, especially:

- Director
- Country
- Cast

This is an important consideration when performing analysis on the Netflix dataset.

# 💡 Business & Content Insights

Although this is primarily an exploratory data analysis project, the findings can support several content-related decisions.

## 1. Content Portfolio Analysis

Understanding the balance between Movies and TV Shows can help evaluate the overall structure of the content catalog.

## 2. Geographic Content Strategy

Country-level analysis can help identify regions that contribute significantly to the Netflix content library.

## 3. Genre Strategy

Genre analysis can help identify frequently represented categories and potential areas for further content research.

## 4. Audience Segmentation

Rating analysis provides information about the different audience categories represented within the catalog.

## 5. Content Lifecycle

Release-year and date-added analysis can help distinguish between older content and newer additions to the platform.

## 6. Content Format

Movie duration and TV Show season analysis provide insight into the formats and lengths represented in Netflix's catalog.

# 📊 Key Business Questions Answered

This project addresses questions such as:

- How many Movies and TV Shows are present in the dataset?
- What percentage of the catalog consists of Movies versus TV Shows?
- How has Netflix content addition changed over time?
- How do Movie and TV Show additions compare across years?
- Which countries contribute the most Netflix titles?
- Which genres appear most frequently?
- What are the most common content ratings?
- What is the typical movie duration?
- How are movie durations distributed?
- How many seasons do Netflix TV Shows typically have?
- Which directors appear most frequently?
- Which actors appear most frequently?
- How does content type vary by country?
- How does content type vary by genre?
- Are there monthly patterns in Netflix content additions?
- What data-quality issues exist in the dataset?

# 📚 EDA Workflow

The project follows this analytical workflow:
```text

             Netflix Dataset
                    │
                    ▼
          Data Understanding
                    │
                    ▼
             Data Cleaning
                    │
                    ▼
          Feature Engineering
                    │
                    ▼
        Exploratory Data Analysis
                    │
          ┌─────────┴─────────┐
          ▼                   ▼
    Univariate Analysis   Bivariate Analysis
          │                   │
          └─────────┬─────────┘
                    ▼
          Statistical Analysis
                    │
                    ▼
             Visualization
                    │
                    ▼
             Key Insights

```
# 🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

- Python for Data Analysis
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Exploratory Data Analysis
- Data Cleaning
- Missing Value Handling
- Data Transformation
- Feature Engineering
- Data Aggregation
- GroupBy Operations
- Cross-tabulation
- String Processing
- Date-Time Processing
- Multi-value Column Processing
- Statistical Analysis
- Data Visualization
- Analytical Thinking
- Business/Content Insight Generation

# 🔮 Future Improvements

The analysis can be expanded with:

- Interactive dashboards using Power BI or Tableau
- Geographic maps showing content distribution
- Advanced time-series analysis
- Genre combinations and co-occurrence analysis
- Director and actor collaboration analysis
- -Content rating by country
- Country-wise genre analysis
- Movie duration trends over time
- TV Show season trends
- Advanced statistical analysis
- Recommendation-system development
- Machine-learning-based content clustering
- NLP analysis of title descriptions
- Sentiment analysis of descriptions
- Automated data pipeline for updated Netflix data

# 📌 Project Limitations

- The dataset represents a snapshot of Netflix's content and may not represent the current Netflix catalog.
Missing values exist in several columns.
- The country, cast, and listed_in columns contain multiple values in individual cells and therefore require transformation before detailed analysis.
- The dataset does not contain important metrics such as views, watch time, revenue, user ratings, or engagement.
- Therefore, conclusions are based on catalog-level information rather than actual viewer behavior.

#🏁 Conclusion

This project demonstrates a complete Exploratory Data Analysis workflow using Python, Pandas, and NumPy on a real-world Netflix dataset.

The analysis began with understanding the dataset structure and identifying data-quality issues. The data was then cleaned and transformed to make it suitable for analysis. Date fields were converted into usable datetime features, while multi-value columns such as countries, genres, and cast members were split and exploded for detailed analysis.

The project analyzed the distribution of Movies and TV Shows, content additions over time, country-level contributions, genre distribution, ratings, movie duration, TV Show seasons, directors, actors, and monthly content patterns.

NumPy was used for statistical analysis of movie durations, including mean, median, standard deviation, minimum, maximum, and percentile calculations.

A major focus of the project was converting raw data into clear visual insights through charts such as bar charts, line charts, histograms, and heatmaps.

Overall, this project demonstrates how Python-based data analysis can transform a raw dataset into structured information and actionable insights. It also demonstrates core skills required for entry-level Data Analyst, Business Analyst, and Product Analyst roles, particularly in data cleaning, exploratory analysis, visualization, and analytical problem-solving.

# ⭐ Project Summary

Netflix Data Analysis is an end-to-end Python EDA project designed to demonstrate practical data analytics skills using a real-world entertainment dataset.

The project combines Pandas for data manipulation, NumPy for numerical analysis, Matplotlib and Seaborn for visualization, and analytical reasoning to transform raw Netflix catalog data into meaningful insights.

The project demonstrates the complete journey from raw data to cleaned dataset, engineered features, exploratory analysis, statistical evaluation, visualization, and final insights, making it a strong portfolio project for demonstrating foundational data analytics capabilities.

# 👨‍💻 Project Author

## Aditya Ujjawal

## Focus Areas
- Data Analytics
- Business Analytics
- Product Analytics
- Python
- SQL
- Power BI
- Data Visualization

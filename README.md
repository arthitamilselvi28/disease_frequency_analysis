# Disease frequency Analysis in Healthcare using Python and pandas

## Project Overview
This project analyzes weekly disease case data using Python and Pandas to identify trends and patterns in common diseases. The dataset includes diseases such as Flu, Dengue, Typhoid, and COVID-19.

The goal of this project is to perform basic data analysis, summarize disease frequency, and visualize the distribution of cases.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- jupyter notebook

## Dataset
The dataset contains weekly records of disease cases with the following columns:

| Column | Description |
|------|-------------|
| Week | Date of the recorded week |
| Disease | Type of disease |
| Cases | Number of reported cases |

Example diseases analyzed:
- Flu
- Dengue
- Typhoid
- COVID-19

## Project Steps

### 1. Data Loading
The dataset was loaded using Pandas.

### 2. Data Exploration
Basic data analysis was performed using:
- `df.describe()`
- `df.info()`

### 3. Data Sorting
The dataset was sorted to identify diseases with the highest number of cases.

### 4. Disease Frequency Analysis
Using Pandas `groupby()`, total cases for each disease were calculated.

Example result:

Flu – Highest number of cases  
Dengue – Lowest number of cases

### 5. Data Visualization
Matplotlib was used to create visual charts showing the distribution of disease cases.

## Key Insights
- Flu had the highest total number of reported cases.
- Dengue had the lowest frequency among the diseases in the dataset.
- Weekly trends show variation in case counts across diseases.

## Project Structure
Healthcare-Disease-Analysis
│
├── disease_analysis.ipynb
├── common_disease.csv
└── README.md


## Learning Outcomes
Through this project I learned:

- Data analysis using Pandas
- Grouping and aggregating datasets
- Sorting and summarizing data
- Creating visualizations using Matplotlib
- Performing basic healthcare data analysis

## Future Improvements
- Add more diseases and longer time periods
- Create advanced visualizations
- Build a dashboard using Power BI or Tableau
- Apply machine learning for disease prediction

## Author
Arthi Tamil Selvi.y,

B.Sc Nursing Graduate transitioning into Data Science

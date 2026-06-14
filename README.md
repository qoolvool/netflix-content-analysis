

Project Description:

Analysis of a Netflix dataset containing over 8,800 movies and TV shows. This project demonstrates:
- Data Cleaning (removing incorrect values)
- Exploratory Data Analysis (EDA)
- Data Visualization

Dataset Source: Kaggle - Netflix Movies and TV Shows (https://www.kaggle.com/datasets/shivamb/netflix-shows)

Key Questions:

1. What percentage of Netflix content is movies vs TV shows?
2. Which genres are the most popular?
3. Which countries produce the most content?
4. How has the amount of content changed over the years?
5. Which content ratings dominate?

Main Insights:

 Movies vs TV Shows:
- Movies: 69.6% (6,128 titles)
- TV Shows: 30.4% (2,676 titles)
- Netflix focuses primarily on movie content

 Top Genres:
1. International Movies (2,752) - 31.2%
2. Dramas (2,427) - 27.6%
3. Comedies (1,674) - 19.0%

 Top Countries:
1. United States (3,686) - 41.8%
2. India (1,046) - 11.9%
3. United Kingdom (804) - 9.1%

 Content Ratings:
- TV-MA (3,207) - Adult audiences
- TV-14 (2,160) - Teen audiences
- TV-PG (863) - Family content

 Yearly Trends:
- Peak: 2018 (1,147 new releases)
- Growth: Exponential increase from 2012-2018
- Decline: Content additions slowed after 2018


Data Cleaning Process

Issue: Column "rating" contained incorrect values like "74 min", "84 min", "66 min"

Solution: Removed 3 rows with invalid data

Result:
- Before: 8,807 records
- After: 8,804 records
- Removed: 3 invalid entries



Tools & Libraries

- Python 3.x
- pandas - Data processing and analysis
- matplotlib - Static visualizations
- seaborn - Enhanced data visualization




Key Conclusions

1. Netflix is movie-focused - 70% of content is movies
2. Adult content dominates - TV-MA and TV-14 make up 76% of all content
3. USA is the main source - Over 40% of all content comes from the United States
4. Dramas and comedies are popular - These genres make up ~47% of all content
5. Content growth has slowed - After 2018, the rate of new content additions decreased



Author: Vadim Kulikov

Portfolio project for Junior Data Analyst position

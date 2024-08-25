# IMDB CinemaScope-Analytics-Excel
Unveiling the Dynamics of Movie Success

### **Background:**

Hollywood Insights Inc. is a data analytics firm specializing in the film and entertainment industry. The company provides in-depth analysis and insights into movie trends, box office earnings, and audience preferences. With an extensive dataset covering various aspects of the movie industry, including movie titles, genres, directors, stars, production companies, budgets, gross earnings, and IMDb scores, Hollywood Insights Inc. plays a crucial role in guiding film studios, independent filmmakers, and media analysts in making informed decisions. As the film industry evolves with emerging trends and changing audience tastes, the need for comprehensive data analysis becomes increasingly vital for predicting success, understanding market dynamics, and identifying key factors that contribute to a movie's popularity and financial success.

### **Objective:**

The project aims to perform a thorough analysis of Hollywood Insights Inc.'s comprehensive movie dataset to uncover insights into the dynamics of the movie industry. We will use advanced Excel techniques to explore various facets of the dataset, including trends in movie genres, financial analysis of movie budgets and earnings, and the impact of directors and stars on movie success. Key tasks involve data cleaning, manipulation, visualization, and the creation of an interactive dashboard that captures the essence of the movie industry's trends and patterns. This project is intended to enhance Hollywood Insights Inc.'s ability to provide strategic guidance to its clients, enabling better decision-making in film production, marketing, and distribution. The analysis will also contribute to understanding the evolving landscape of the movie industry, potentially influencing future trends in filmmaking and audience engagement.

**Dataset Description:**

[**Dataset link:**](https://github.com/ShouvikSaha504/CinemaScope-Analytics---Excel/blob/4b3bc40f5d7e163c843d6e95ca47b8b9d3f01bbf/movies.csv)

The "movies.csv" file contains data about various movies. Here's an overview of its structure and the type of data it includes:

1. **name**: Movie name (String)
2. **rating**: Movie rating (String)
3. **genre**: Genre of the movie (String)
4. **year**: Year of release (Integer)
5. **released**: Release date (String, includes country)
6. **score**: IMDb score (Float)
7. **votes**: Number of votes on IMDb (Float)
8. **director**: Director's name (String)
9. **writer**: Writer's name (String)
10. **star**: Main star's name (String)
11. **country**: Country of origin (String)
12. **budget**: Production budget (Float)
13. **gross**: Gross earnings (Float)
14. **company**: Production company (String)
15. **runtime**: Runtime in minutes (Float)

### **Part 1: Excel Data Analysis: Manipulation, Formulas and Functions**

[**Part I link:**](https://github.com/ShouvikSaha504/CinemaScope-Analytics---Excel/blob/b26e4dcbe0d5a66132dfd52ab6761c790840a0b8/CinemaScope-Analytics-Shouvik%20Saha%20-%20Part%20I.xlsx)

**Part I Overview:** This project involves a comprehensive analysis of a movies dataset, focusing on handling missing data, sorting and filtering by release year and IMDb score, and analyzing genre distribution. It includes comparing budget and gross earnings with scatter plots, categorizing IMDb scores, and visualizing country-wise production. Additional tasks involve identifying top directors by average earnings, calculating average runtimes, and examining trends in movie ratings and profitability. The analysis extends to highlighting high-budget movies, exploring star impact, segmenting movies by IMDb score, and tracking budget and earnings trends over time. The project also includes predicting future earnings, analyzing revenue-to-budget ratios, and exploring the network of director-star collaborations.


## Methodology

## Data Import and Cleaning
- **Import Data:** Loaded the movie dataset into Excel.
- **Clean Data:**
  - **Handling Null Values:** Identified and addressed missing values by imputing with mean, median, or using other methods as appropriate.
  - **Feature Engineering:** Created new columns or transformed existing features to enhance the dataset for analysis.

## Analysis and Visualization
- **Data Sorting and Filtering:**
  - **Sort Data:** Sorted the dataset by `year of release` and `gross earnings` using Excel’s `SORT` function.
  - **Filter Data:** Applied filters to display movies with an IMDb score greater than 8.0.

- **Pivot Tables and Charts:**
  - **Pivot Tables:** Utilized pivot tables to analyze distributions, such as genre-wise movie counts, average budgets, and gross earnings.
  - **Charts:**
    - **Line Chart:** Visualized trends over time for metrics like IMDb scores and gross earnings.
    - **Bar Chart:** Compared movie production by country and identified top production companies.
    - **Scatter Plot:** Examined the correlation between budget and gross earnings.
    - **Pie Chart:** Showed the distribution of movies across different genres and countries.

- **Forecasting:**
  - **Predictive Analysis:** Applied Excel’s forecasting tools to project future industry trends, focusing on gross earnings based on historical data, genre, budget, and IMDb score.

## Insights and Trends
- **Correlation Analysis:** Analyzed correlations between movie runtime and IMDb score.
- **Profitability Calculation:** Created a new column to calculate profitability by subtracting budget from gross earnings.
- **Genre and Country Analysis:** Assessed the distribution of movies by genre and country, identifying trends and patterns.
- **Budget and Earnings Trends:** Analyzed how average movie budgets and earnings have evolved over time.


### **Part 2: Building an Excel Dashboard**

Develop a comprehensive and interactive Excel dashboard that integrates key metrics and insights derived from the "movies.csv" dataset. The dashboard should provide a holistic view of the movie industry trends, focusing on movie performance, genre popularity, director and star impact, and financial analysis of movie earnings.


## Dashboard Development
- **Importing Charts:**
  - **Charts Integration:** Imported various charts into an Excel sheet to build a visually appealing and interactive dashboard.

## Key Insights

- **Breakdown of Movies:**
  - **Line Charts:** Analyzed decade-wise trends to understand movie distribution and performance over time.

- **Movie Analysis:**
  - **Budget vs. Gross Earnings:** Utilized a stacked bar chart to compare the budget and gross earnings of the top 5 movies. 'Avengers: Endgame' and 'Avatar' are the highest-grossing movies.

- **Distribution of Movies by Ratings:**
  - **Pie Chart:** Illustrated the distribution of movies across different ratings to highlight rating trends. R-rated movies account for around 49%, followed by PG-13 rated movies.

- **Number of Movies by Genre:**
  - **Bar Chart:** Displayed the count of movies across various genres, identifying the most and least popular genres. Action and comedy are the most popular genres, while musical and music are the least popular genres.

- **Slicers:**
  - **Movie Type:** Implemented slicers to categorize movies as 'Bad', 'Mediocre', or 'Good' based on their performance metrics. 
  - **Genre-wise Analysis:** Enabled interactive genre-wise analysis using slicers.
  - **Rating-wise Analysis:** Provided rating-wise insights using slicers.

## Financial Insights
- **Total Profit:** Calculated the total profit across all movies, amounting to $349 billion.
- **Most Successful Genre:** Identified 'Animation' as the most successful genre based on gross earnings.
- **Most Popular Genre:** Determined 'Comedy' as the most popular genre based on the number of movies.

[**Dashboard Link:**](https://github.com/ShouvikSaha504/CinemaScope-Analytics---Excel/blob/b26e4dcbe0d5a66132dfd52ab6761c790840a0b8/CinemaScope-Analytics-Part%20II%20-%20Shouvik%20Saha.xlsx)


### Dashboard Snap
![CinemaScope-Analytics Dashboard](https://github.com/user-attachments/assets/3f498b30-72ae-46c1-84f4-928afb12128c)

### Actionables: 
Use successful movies like Avengers: Endgame and Avatar in your marketing to show their success and attract attention. Partner with studios or distributors for joint promotions or exclusive content. Focus on creating and promoting R-rated content to appeal to that audience and adjust your marketing to match their interests.

### Conclusion

The dashboards and analyses provide a comprehensive view of the movie industry, blending financial metrics and creative insights. From identifying key trends in decade-wise movie performance to evaluating genre popularity and production house success, the data-driven approach offers valuable perspectives for producers, investors, and creators. By visualizing financial correlations, genre distributions, and forecasting future trends, this project equips stakeholders with actionable insights to make informed decisions and strategize effectively within the dynamic world of filmmaking.



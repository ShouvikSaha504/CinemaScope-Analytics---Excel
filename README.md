# CinemaScope-Analytics-Excel
Unveiling the Dynamics of Movie Success

### **Background:**

Hollywood Insights Inc. is a data analytics firm specializing in the film and entertainment industry. The company provides in-depth analysis and insights into movie trends, box office earnings, and audience preferences. With an extensive dataset covering various aspects of the movie industry, including movie titles, genres, directors, stars, production companies, budgets, gross earnings, and IMDb scores, Hollywood Insights Inc. plays a crucial role in guiding film studios, independent filmmakers, and media analysts in making informed decisions. As the film industry evolves with emerging trends and changing audience tastes, the need for comprehensive data analysis becomes increasingly vital for predicting success, understanding market dynamics, and identifying key factors that contribute to a movie's popularity and financial success.

### **Objective:**

The project aims to perform a thorough analysis of Hollywood Insights Inc.'s comprehensive movie dataset to uncover insights into the dynamics of the movie industry. We will use advanced Excel techniques to explore various facets of the dataset, including trends in movie genres, financial analysis of movie budgets and earnings, and the impact of directors and stars on movie success. Key tasks involve data cleaning, manipulation, visualization, and the creation of an interactive dashboard that captures the essence of the movie industry's trends and patterns. This project is intended to enhance Hollywood Insights Inc.'s ability to provide strategic guidance to its clients, enabling better decision-making in film production, marketing, and distribution. The analysis will also contribute to understanding the evolving landscape of the movie industry, potentially influencing future trends in filmmaking and audience engagement.

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

1. **Missing Data Handling:** Identify and address missing data in the movies dataset. Are there any patterns in the missing data that can be noted?
2. **Data Sorting and Filtering:** Sort the movies by year of release and by gross earnings. Then, filter the dataset to show only movies with an IMDb score greater than 8.0.
3. **Analysis of Movie Genres:** Analyze the distribution of movies across different genres. Which genre has the most movies, and which has the least?
4. **Budget and Gross Earnings Comparison:** Compare the budget and gross earnings of movies. Create a scatter plot to visualize if there's a correlation between them.
5. **IMDb Score Categorization:** Categorize movies into 'High', 'Medium', and 'Low' based on their IMDb scores. Define the thresholds for these categories.
6. **Country-wise Movie Production:** Analyze which countries have produced the most movies. Create a pie chart to represent this data.
7. **Director Analysis:** Who are the top 5 directors with the highest average gross earnings? Use formulas to calculate and sort this information.
8. **Runtime Analysis:** Calculate the average runtime of movies. How does this vary across different genres?
9. **Top Grossing Movies by Year:** Identify the top grossing movie of each year in the dataset.
10. **Rating Popularity Over Time:** Analyze how the popularity of different movie ratings (G, PG, PG-13, R, etc.) has changed over the years.
11. **Conditional Formatting for High Budget Movies:** Use conditional formatting to highlight movies with budgets above a certain threshold.
12. **Star Impact Analysis:** Investigate if there's a trend between the main star of a movie and its gross earnings or IMDb score.
13. **Profitability Calculation:** Create a new column to calculate the profitability of each movie (gross earnings minus budget).
14. **Decade-wise Movie Analysis:** Categorize movies into decades based on their release year and analyze the trend of average movie scores and gross earnings per decade.
15. **Pivot Table for Genre Analysis:** Use a pivot table to analyze the average budget and gross earnings for each genre.
16. **Correlation Analysis:** Determine if there's any correlation between the runtime of a movie and its IMDb score.
17. **Budget Evolution Over Time:** Analyze how the average movie budget has changed over the years.
18. **Top Companies in Movie Production:** Which production companies have released the most movies? Create a bar chart to represent this data.
19. **Analysis of Movie Release by Month:** Investigate if there is a preferred month or season for releasing movies. Does this trend differ by genre?
20. **Score-based Movie Segmentation:** Segment movies into different categories based on their IMDb score and analyze the average budget and gross earnings in each segment.
21. **Time-Series Analysis of Genre Popularity:** Conduct a time-series analysis to evaluate the popularity of movie genres over the years. (Organize the data by year and genre, then calculate the number of movies or total gross earnings per genre per year. Create a line chart or area chart to visualize the trends over time.)
22. **Predictive Analysis for Future Gross Earnings:** Use the historical data to predict the future gross earnings of movies based on genre, budget, and IMDb score.(Utilize Excel's advanced forecasting tools.)
23. **Revenue and Budget Ratio Analysis Over Time**: Calculate and analyze the ratio of total yearly gross earnings to the total yearly budgets of all movies released each year. How has this ratio evolved over the years covered in the dataset?(Aggregate data year-wise, calculate the total gross earnings and total budgets for each year, and then compute the ratio. Then conduct a trend analysis to understand how this profitability indicator has changed over time. Creating a line chart to visualize this trend would be essential.)
24. **Network Analysis of Directors and Stars:** Analyze the network of collaborations between directors and stars. Identify which pairs of directors and stars most frequently work together and the average gross earnings of their movies. (Use advanced data manipulation to create this matrix and then apply functions to calculate frequencies and averages.)

# Methodology

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
  - **Budget vs. Gross Earnings:** Utilized a stacked bar chart to compare the budget and gross earnings of the top 5 movies.

- **Distribution of Movies by Ratings:**
  - **Pie Chart:** Illustrated the distribution of movies across different ratings to highlight rating trends.

- **Number of Movies by Genre:**
  - **Bar Chart:** Displayed the count of movies across various genres, identifying the most and least popular genres.

- **Slicers:**
  - **Movie Type:** Implemented slicers to categorize movies as 'Bad', 'Mediocre', or 'Good' based on their performance metrics.
  - **Genre-wise Analysis:** Enabled interactive genre-wise analysis using slicers.
  - **Rating-wise Analysis:** Provided rating-wise insights using slicers.

## Financial Insights
- **Total Profit:** Calculated the total profit across all movies, amounting to $349 billion.
- **Most Successful Genre:** Identified 'Animation' as the most successful genre based on gross earnings.
- **Most Popular Genre:** Determined 'Comedy' as the most popular genre based on the number of movies.


### Conclusion

The dashboards and analyses provide a comprehensive view of the movie industry, blending financial metrics and creative insights. From identifying key trends in decade-wise movie performance to evaluating genre popularity and production house success, the data-driven approach offers valuable perspectives for producers, investors, and creators. By visualizing financial correlations, genre distributions, and forecasting future trends, this project equips stakeholders with actionable insights to make informed decisions and strategize effectively within the dynamic world of filmmaking.






### Dashboard Snap
![CinemaScope-Analytics Dashboard](https://github.com/user-attachments/assets/3f498b30-72ae-46c1-84f4-928afb12128c)


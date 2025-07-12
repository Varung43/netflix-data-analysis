# netflix-data-analysis
"EDA project using Python on Netflix dataset from Kaggle"

📄 Netflix Data Analysis – Case Study (Q&A Format)
1. What was the objective of this project?
To analyze Netflix’s content library to uncover insights such as:

Movies vs TV Shows distribution
Year-wise content additions
Top countries producing content
Most common genres and categories

2. What tools and technologies did you use?
Python
Pandas – for data manipulation and cleaning
Matplotlib & Seaborn – for data visualization
Jupyter Notebook

3. What steps did you follow?
Downloaded the dataset from Kaggle
Loaded the data using Pandas
Cleaned the data (handled missing values, converted date columns)
Extracted new features like year_added and month_added
Performed EDA and created multiple visualizations

4. What were the key insights?
📊 Movies dominate over TV Shows on Netflix
📅 Netflix added the most content during 2019–2020
🌍 United States, India, and UK lead in content creation
🎭 Drama, International Movies, and Documentaries are the most frequent genres

5. What challenges did you face?
Columns like director, cast, country had missing values
date_added was in string format — required conversion to datetime
listed_in (genre) contained multiple values in one cell
✅ I used .fillna(), .dropna(), .explode() and to_datetime() to solve these.

6. What is the outcome?
Completed a well-documented Jupyter Notebook
Plotted 5+ meaningful visualizations


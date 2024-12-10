ICC Men's Cricket World Cup - A Journey Through History
This project analyzes the ICC Men's Cricket World Cup matches held between 1975 and 2023. It involves data preparation, sentiment analysis using a Hugging Face model, and the creation of an interactive dashboard to provide insights into the tournament's history.

Key Components

1. Data Preparation
Combined and cleaned data from 13 CSV files representing each World Cup series.
Processed columns to remove duplicates, handle missing values, and create new derived features such as:
Match Status: Whether the match was played or abandoned.
Winning Team: Identified the victorious team based on match results.
Expanded best_batters and best_bowlers columns into detailed columns for names and performance statistics.

2. Sentiment Analysis
Applied a Hugging Face model to analyze the sentiment of 375 commentary excerpts from the 2023 World Cup final match.
Added a new column, "sentiment", to classify each commentary line into positive, neutral, or negative sentiment.
Visualized the sentiment distribution for enhanced understanding.

3. Interactive Dashboard
Designed an interactive dashboard using Plotly Dash to tell the story of the World Cup data through dynamic and engaging visualizations.

Key features include:

Bar charts, line graphs, and pie charts.
Filters for exploring data by year, teams, or match categories.
Insights into team performances, player statistics, and trends across the tournaments.

How to Use

Clone this repository to your local system.
Run the Jupyter notebooks to explore the data preparation and sentiment analysis steps.
Launch the dashboard using the provided script to interact with the visualizations.
Project Goals
This project aims to showcase the power of data analysis, machine learning, and visualization tools in uncovering insights from historical datasets.

Tools & Libraries Used

Pandas: For data manipulation and cleaning.
Hugging Face Transformers: For sentiment analysis.
Plotly Dash: For creating the interactive dashboard.
Python: Core programming language.
Contributions
Feel free to fork this repository, make changes, and open pull requests for contributions or suggestions!

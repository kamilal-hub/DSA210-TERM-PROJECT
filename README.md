# DSA210 Term Project: TV Series Analysis
Milestone 1 - Project Progress
In this milestone, I have successfully completed the following steps:

*   Data Collection:I expanded the dataset to include 250+ TV series, pulling critical features like `averageRating`, `numVotes`, and `startYear` from IMDb.
*   Data Enrichment:I integrated a Python-based retry mechanism to pull Google Trends data via API. 
*   Exploratory Data Analysis (EDA):I create comprehensive visualizations (histograms, scatter plots, and a correlation heatmap) to analyze the underlying distributions and relationships between IMDb ratings, audience size, and release years.
*   Hypothesis Testing:
    *   I conducted a Pearson Correlation test, revealing a statistically significant but weak positive correlation (0.30) between a show's rating and its mass-market popularity.
    *  I performed an Independent T-Test to compare classic vs. modern shows, we can see successfully proving that series released before 2017 have a statistically significant higher average rating than newer ones.

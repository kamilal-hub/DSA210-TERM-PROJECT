# DSA210 Term Project: TV Series Analysis
Milestone 1 - Project Progress
In this milestone, I have successfully completed the following steps:

*   Data Collection:I expanded the dataset to include 250+ TV series, pulling critical features like averageRating, numVotes, and startYear from IMDb.
*   Data Enrichment:I integrated a Python-based retry mechanism to pull Google Trends data via API. 
*   Exploratory Data Analysis (EDA):I create comprehensive visualizations (histograms, scatter plots, and a correlation heatmap) to analyze the underlying distributions and relationships between IMDb ratings, audience size, and release years.
*   Hypothesis Testing:
    *   I conducted a Pearson Correlation test, revealing a statistically significant but weak positive correlation (0.30) between a show's rating and its mass-market popularity.
    *  I performed an Independent T-Test to compare classic vs. modern shows, we can see successfully proving that series released before 2017 have a statistically significant higher average rating than newer ones.

## Milestone 2 - Machine Learning (Clustering)

In this milestone, I applied unsupervised machine learning to find hidden patterns and group the TV series. I successfully completed the following steps:

* Data Preprocessing:I used StandardScaler to scale features like averageRating, numVotes, and peak_search so they contribute equally to the algorithm.
* Finding the Optimal K:I applied the "Elbow Method" by plotting the Sum of Squared Errors (SSE). The graph clearly showed a "elbow" at k=4, indicating it as the optimal number of clusters.
* K-Means Clustering:I trained a K-Means algorithm with 4 clusters to group the TV series based purely on their characteristics, without giving the model any predefined labels.
* Data Profiling & Visualization:I created a scatter plot to visualize the results and analyzed the data. I successfully identified 4 distinct TV show profiles:
    * Cluster 3 (The Mega-Phenomena):Shows with both exceptionally high ratings and record-breaking audience votes (e.g., Game of Thrones).
    * Cluster 0 (Popular & High Quality):Mainstream hits with great ratings and a very large fan base (e.g., The Boys, Better Call Saul).
    * Cluster 2 (Hidden Gems):** Critically acclaimed shows with high ratings but a smaller, more niche audience (e.g., Succession, Severance).
    * Cluster 1 (Average Quality, High Popularity):Widely watched shows that have average or lower IMDb ratings (e.g., The Flash, 13 Reasons Why).

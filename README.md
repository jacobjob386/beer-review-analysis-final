# Beer Review Analysis and Recommendation System
This project analyzes a large beer review dataset to understand how different sensory attributes and reviewer behaviors influence beer ratings. The project also builds a simple machine learning model to predict beer ratings and a recommendation system that suggests similar beers based on flavor characteristics.

The entire analysis, visualizations, modeling, and recommendation system are implemented in beer_review.ipynb, where all project objectives are organized step by step.

Datasets
The project uses the following datasets:

beer_info.csv – Contains information about beers such as beer name, brewery, style, and alcohol content.

beer_reviews.csv – Contains user reviews and overall ratings for beers.

review_details.csv – Contains detailed sensory scores such as aroma, taste, appearance, and palate.

These datasets are cleaned and merged to create beer.csv, which is the final processed dataset used for analysis and modeling.

Project Objectives
The project consists of several analytical and modeling tasks that explore different aspects of beer reviews.

The analysis includes:

Understanding the distribution of beer ratings

Studying relationships between sensory attributes and overall scores

Analyzing reviewer behavior and identifying active reviewers

Exploring rating biases and reviewer consistency

Building a machine learning model to predict beer ratings

Creating a recommendation system that suggests beers with similar flavor profiles

All these objectives are implemented and explained inside beer_review.ipynb.

Machine Learning Model
A regression model is trained to predict the overall beer rating using features such as aroma score, taste score, palate score, appearance score, and alcohol content. The model evaluation uses metrics such as R² score, RMSE, and MAE.

The results show that taste and palate scores have the strongest influence on overall beer ratings.

Beer Recommendation System
A content-based recommendation system is created using beer flavor profiles. Each beer is represented using its average sensory attributes, and similarity between beers is calculated using cosine similarity.

Given a beer name, the system can recommend other beers with similar flavor characteristics.

Key Insights
Most beer ratings fall within a relatively high range, indicating that reviewers generally rate beers positively. A small group of reviewers contributes a large portion of the reviews, while most users review only a few beers.

Sensory attributes such as taste, aroma, and palate play the most important role in determining the final rating of a beer. These same attributes are also useful for identifying beers with similar flavor profiles.


## Amazon-Food-Reviews-Prediction

The main purpose of this system is to study the food reviews trends from Amazon's dataset and build prediction models to predict the sentiments and helpfulness of products based on various other factors explored from the dataset. 
**DATASET:**
The Amazon Fine Food Reviews dataset consists of 568,454 food reviews Amazon users left up to October 2012. Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
This dataset consists of a single CSV file, Reviews.csv, and a corresponding SQLite table named Reviews in database SQLite. The columns in the table are:
•	Id
•	ProductId - unique identifier for the product
•	UserId - unique identifier for the user
•	ProfileName
•	HelpfulnessNumerator - number of users who found the review helpful
•	HelpfulnessDenominator - number of users who indicated whether they found the review helpful
•	Score - rating between 1 and 5
•	Time - timestamp for the review
•	Summary - brief summary of the review
•	Text - text of the review

For the purpose of this project, the analysis is conducted on 9000 reviews. 
**IMPLEMENTATION:**
•	Performed sentiment analysis on Amazon Fine Food Reviews Dataset using Syuzhet Package in R
•	Generated polarity for each review and the corresponding summary
•	Extracted the product title, description and product group using Amazon API with python scripts
•	Created visualizations to find interesting patterns among dataset variables
•	Built a prediction model to predict if a review is positive or negative
•	Created visualizations to find which product group is more helpful 



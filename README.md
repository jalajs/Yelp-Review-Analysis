# Analysis of Yelp Businesses and User Reviews
## By: Noah Skelton, Jalaj Singh, Matthew Spooner and Elizabeth Ronan

We analyzed data taken from Yelp to find trends that impact good and bad reviews. We used machine learning algorithms to predict the sentiment of the review text. Additionally we conducted an independent samples t-test and an ANOVA test to determine the effect of user review count on their overall "usefulness".


**Method:** Our dataset consists of 3 columns which we focus on. The stars, text, number of 'useful' left on a review. Using this dataset, we tested a hypothesis about the number of reviews impacting the number of 'useful''s a review receives. We also used the dataset to predict the sentiment of a review from the text column.

**Results:** During the hypothesis testing we found that, while assumptions for our tests were not quite met, we observed significant differences in the average "useful" rating of users with a large number of reviews compared to those with few. In particular, we saw in our t-test that those with > 25 reviews had a typically higher average "usefulness" than those with < 25 reviews. Additionally, in our ANOVA we saw that those with > 14 reviews had a higher "usefulness" than those in groups of 1-2 reviews, and 3-14 reviews. After features extraction, we found that key words like "wait", "place" , "service" were the most important to a review. Our machine learning models predicted sentiment with great accuracy, with LSV and Logistic regression both receiving an approximately 91% accuracy.

**Discussion:** For the future, we would like to run this analysis on a larger dataset that is more balanced i.e. does not contain a substantially large amount of positive reviews. A more precise analysis could involve predicting star rating instead of 'positive' vs 'negative' sentiment of reviews.

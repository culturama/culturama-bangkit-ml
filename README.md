# culturama-bangkit-ml
Repository for machine learning

Member of Machine Learning part :
1. M200BSY0713 – Muhammad Irfan Rifki – Universitas Diponegoro
2. M200BSY1727 – Fedro Dava Ferenzo – Universitas Diponegoro
3. M200BSY0195 – Muhammad Rafli – Universitas Diponegoro

The model we created is a collaborative filtering recommender system, which is a model that contains an automatic recommendation system based on the results of a survey that will be filled in by each user as well as the rating given by the user to each content so that later users will get recommendations that best suit their respective preferences. After we have finished building this model, we will implement this model into an apps.

Collaborative filtering is a technique that can filter items that a user might like based on reactions from similar users. This is done through the process of searching a large group of people and finding a smaller set of users with similar tastes to a particular user. This is done by looking at the items they like and combining them to create a ranked list of suggestions. There are many ways to determine which users are similar and combine their choices to create a list of recommendations.

1. Data Loading

This step used to retrieve the data that will be used.
At this stage we take data from Kaggle.

2. Data Understanding (EDA)

This step used to investigate data regarding characteristics, patterns, anomalies, and checking assumptions. At this stage we carry out data exploration, such as checking the data type for each column and the amount of data from each column.

3. Data Preparation

This step used to prepare raw data so that it is ready for further processing and analysis.
At this step, what we do is deleting unused columns, check for missing values,
and checking for duplicate data so that the data to be modeled is clean with no errors.

4. Model Development

This step used to build a model that will be processed.
The step we carry out are splitting training data and validation data and dividing train data with test data and then after, it builds our model using collaborative filtering.

5. Conclusion

The last step were used to draw a conclusion from the results that have been carried out.
At this step we can conclude that the system has succeeded in making good recommendations using a collaborative filtering approach.

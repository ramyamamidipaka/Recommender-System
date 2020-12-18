# Recommender-System

Recommendation System is a subclass of information filtering system that seeks to predict the “rating” or “preference” a user would give to an item.Recommendation Systems are utilized in a variety of areas including movies, music, news, books, research articles, search queries, social tags, and products in general. The main aim of recommendation systems are to recommend relevant items to a user based on historical data.

1. BUSINESS PROBLEM
To understand the power of recommendation systems, it is easiest to focus on Netflix, whose state of the art recommendation system keeps us in front of our TVs for hours. However, recommenders are extremely diverse, playing a role in cross-selling products, identifying employee candidates who have similar skill sets, and finding customers who will respond to promotional messaging. And these examples only just scratch the surface of how recommendations systems can be used.

Although recommenders can be very complex, there are two simple approaches that act as a good starting point.

Content based filtering: uses item features to recommend similar items to the ones that a user has previously liked or interacted with. Pandora‘s music genome project identifies musical attributes for each song and uses that information to find similar songs and make recommendations.

Collaborative filtering: identifies items that a user will like based on how similar users rated each item. Netflix identifies shows and movies users will enjoy by determining which content similar users watched.

In this project, we are going with collaborative filtering. Within the group of collaborative filtering, the two most well-known distinct approaches are:

Memory-based models calculate the similarities between users / items based on user-item rating pairs.
Model-based models use some sort of machine learning algorithm to estimate the ratings. A typical example is singular value decomposition of the user-item ratings matrix.
Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix use those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be made better.

Credits: https://www.netflixprize.com/rules.html

Problem Statement
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

References
https://medium.com/@narendra09b/recommendation-systems-6cedb4cb7cec
https://towardsdatascience.com/building-and-testing-recommender-systems-with-surprise-step-by-step-d4ba702ef80b
https://laptrinhx.com/a-simple-approach-to-building-a-recommendation-system-452318104/
Performance metric
We use mainly MAPE and RMSE mainly as performance metrics for this problem. We can find more about them in the following links given below. \

Mean Absolute Percentage Error: https://en.wikipedia.org/wiki/Mean_absolute_percentage_error
Root Mean Square Error: https://en.wikipedia.org/wiki/Root-mean-square_deviation

Machine Learning Objective and Constraints
To Minimize RMSE.
Try to provide some Interpretability.

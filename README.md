# Recommendations-with-IBM

For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles I think they will like.


This project is divided into the following:

1. Exploratory Data Analysis </br>
  Before making recommendations of any kind, |I need to explore the data I am working with for the project. Dive in to see what I can find. There are some basic, required questions to be answered about the data I am working with throughout the rest of the notebook. I used this space to explore, before I dive into the details of my recommendation system in the later sections.

2. Rank Based Recommendations </br>
  To get started in building recommendations, I will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering </br>
  In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. I will implement this next.

4. Content Based Recommendations (EXTRA - NOT REQUIRED) </br>
  Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, I might come up with some extremely creative ways to develop a content based recommendation system.

5. Matrix Factorization </br>
  Finally, I will complete a machine learning approach to building recommendations. Using the user-item interactions, I will build out a matrix decomposition. Using my decomposition, I will get an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I will finally discuss which methods I might use moving forward, and how I might test how well my recommendations are working for engaging users.

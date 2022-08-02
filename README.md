# Recommendation_System
Pizza recommender
Implementation of a recommender for pizza based on ratings given by users to other pizzas, user behaviour includes ratings on items. In this manner, the model finds an association between the users and the items. The model is then used to predict the item or a rating for the item in which the user may be interested. 

# Types of Recommender Systems: #
Recommender systems are typically classified into the following categories:
1) Content-based filtering
2) Collaborative filtering
3) Hybrid systems

# Algorithms used for recommendation #
1) SVD 
2) K nearest neighbours
3) more deep learning and colaborative filtering techniques (https://github.com/microsoft/recommenders.git)

NOTE:
1) data is engineered to resemble movielens data using realistic ratings for pizza. Use the data in csv folder for SVD model.
2) cold start problem is resolved by taking input from user and adding new data in original data.
3) I have used colaborative filtering using SVD.

# References and material to learn #
[1] https://towardsdatascience.com/recommendation-systems-a-review-d4592b6caf4b
[2]	https://docs.aws.amazon.com/machine-learning/latest/dg/cross-validation.html
[3]	https://medium.com/recombee-blog/machine-learning-for-recommender-systems-part-1-algorithms-evaluation-and-cold-start-6f696683d0ed
[4]	https://www.analyticsvidhya.com/blog/2021/07/recommendation-system-understanding-the-basic-concepts/
[5]	https://learn.co/lessons/dsc-4-39-04-singular-value-decomposition-numpy-scipylab




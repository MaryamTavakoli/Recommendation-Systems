 In this project, I explore two methods?matrix factorization and neural collaborative filtering?to predict how users rate movies. I use data from MovieLens, that you can find here (https://grouplens.org/datasets/movielens/)

The matrix factorization method predicts ratings by computing the inner product of user and movie embedding vectors. I find that this simple model relies heavily on the bias component of user and movie embeddings. The user behavior is mainly determined by her/his bias in rating. The key feature for describing movies is the mainstream bias. Highly rated movies with widespread agreement have a positive bias, while those with less consensus have a negative bias.

In the neural collaborative filtering model, ratings are determined by a non-linear function of user and movie features. This non-linearity helps capture interactions between different aspects of users and movies, leading to more accurate predictions.

However, these models have a limitation?they struggle to accurately predict ratings for less active users or movies with fewer ratings.



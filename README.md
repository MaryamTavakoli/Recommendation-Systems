In this project, I examine matrix factorization and neural collaborative filtering methods to predict movie ratings by users. 
I use MovieLens data from https://grouplens.org/datasets/movielens/ 
Matrix factorization method uses the inner product of the user and movie embedding vectors to predict rating. We find that, predicted ratings by this simple model are mainly based on 
the bias component of movie and user embeddings. The most important feature describing movies is the mainstream bias. Movies with strong consessus on their rating has higher positive 
bias and they are more popular. 
In neural collaborative filtering model, ratings are a non-linear function of user/movie features. This non-linearity makes it possible to explore intercations between different components 
describing users/movies and provide more accurate prediction.  
The week point of these models is that less active users or less rated movies can not be trained accurately. 

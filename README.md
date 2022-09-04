# Cold start problem in recommender systems

Collaborative filtering (CF) is mechanism for recommendations: it generates recommendations for a user by utilizing the observed ratings of other users whose past ratings are correlated with the target user. The recommender systems face a problem when it comes to new users and/or new items, this is a well-known problem, commonly referred to as the **cold start** problem.

There are two types of cold-start problems:
  - User cold-start problems: 
    When there is almost no information available about the user, the user cold-start problem arises.
  - Product cold-start problems: 
    When there is almost no information about the product, the product cold-start problem arises.

One approach to cold start problem would be to leverage meta data for estimating the taste of new users and items based on similar users and items. However, as meta data is not always available, as an alterative, the recommender system could explicitly ask the new user's ratings on some *seed* items.

In this project, we determine the seeds by locating the *representatives* in a recommender system. Roughly speaking, representatives are those users whose linear combinations of tastes would accurately approximate other users (the same for items).


## Datasets used in this project are:
  1) Netflix movie rating dataset (https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset)
  2) Lastfm dataset (https://www.upf.edu/web/mtg/lastfm360k)
  3) Movie lens dataset (https://grouplens.org/datasets/movielens)

## Literature
  - https://dl.acm.org/doi/10.1145/2043932.2043943
  - https://pandas.pydata.org/
  - https://scipy.org/

## Authors
* [Ognjen Milinković](https://github.com/ognjenivuk)
* [Anja Veličković](https://github.com/anjavelickovic)



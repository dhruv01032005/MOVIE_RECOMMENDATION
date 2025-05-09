# MOVIE_RECOMMENDATION

This project is done as an individual.

In this project I have used -
1. The library Apriori which helps to find the movies with support, confidence and lift above a specific value defined by us.
2. I have used matrix factorization whcih predicts according to your rating which movie will you rate more and which movie will you rate less.

## Metrics

1. Support(X) = No. of people watched Movie X / Total No. of people
2. Confidence(X -> Y) = Support(X union Y) / Support(X)
3. Lift(X -> Y) = Confidence(X - > Y) / Support(Y)

## References

1. https://nipunbatra.github.io/ml-teaching/notebooks/movie-recommendation-knn-mf.html
2. https://unstop.com/practice/machine-learning-ai-project/netflix-movie-suggestions

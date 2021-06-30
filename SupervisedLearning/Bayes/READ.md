# Bayes

This R Jupyter notebook uses Bayes to classify mail as spam or not.
To solve the problem of a spam classifier. 
We count the number of ocurrences of certain words (not numbers, not symbols and at least appears twice) in all the training set
for both, normal mail and spam. Then we multiply all the probabilities of ocurrence as if they where independent.
Finally, we decide if it is spam or not depending on the biggest probability.

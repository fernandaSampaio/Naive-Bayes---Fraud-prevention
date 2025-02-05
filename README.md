# Naive-Bayes---Fraud-prevention
Naive Bayes is a classification method based on Bayes’ Theorem.

## What is Bayes’ Theorem?
Bayes’ Theorem is a formula that helps update the probability of an event based on new information.
Imagine you have a box with 70 red balls and 30 blue balls. You randomly pick a ball, and it is red. Now, you want to know the probability that the next ball you pick will also be red.

## How Naive Bayes Works:

Learn from the Past: First, you look at movies your friends have already watched and see if they liked them or not. You record which features of those movies were most common among the ones that were well received.
Make Predictions: When a new movie comes out, you use what you’ve learned to make a prediction. You calculate the probability that a person will like the movie, given that it has features similar to the movies your friends liked in the past.
Independence: The “naive” in Naive Bayes comes from the assumption that all features of the movie (such as genre, actor, music) are independent of each other. That is, the model assumes that a person’s liking for a genre does not influence their liking for an actor.
Types of Naive Bayes:

Gaussian Naive Bayes: Assumes that the features follow a normal (Gaussian) distribution.
Multinomial Naive Bayes: Primarily used for categorical data, such as in text classification problems.
Bernoulli Naive Bayes: Used when the data is binary (e.g., presence or absence of a feature).
Disadvantages:

Independence Assumption: The assumption that features are independent may not hold true in practice, which can affect the accuracy of the model.

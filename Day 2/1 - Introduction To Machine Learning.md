# Introduction To Machine Learning
We have covered that Machine Learning is the science of making computers performs tasks without being explicitly programmed. This paves way for making predictions, which is one of the key functionality and popular technique of Machine Learning. 
Machine learning is directly linked to statistical techniques.    

# Definition
Tom Mitchell provides a more modern definition: <b>"A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E."</b>

<b>Example: playing checkers.</b>
<b>E</b> = the experience of playing many games of checkers
<b>T</b> = the task of playing checkers.
<b>P</b> = the probability that the program will win the next game.

In general, any machine learning problem can be assigned to one of two broad classifications:
* Supervised learning 
* Unsupervised learning.
# Supervised Learning
In supervised learning, we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output.
Supervised learning problems are categorized into "regression" and "classification" problems. In a regression problem, we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function.
In a classification problem, we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories.

### Example 1:

Given data about the size of houses on the real estate market, try to predict their price. Price as a function of size is a continuous output, so this is a regression problem.
We could turn this example into a classification problem by instead making our output about whether the house "sells for more or less than the asking price." Here we are classifying the houses based on price into two discrete categories.

### Example 2:

* (a) Regression - Given a picture of a person, we have to predict their age on the basis of the given picture

* (b) Classification - Given a patient with a tumor, we have to predict whether the tumor is malignant or benign.

# Unsupervised Learning
Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.
We can derive this structure by clustering the data based on relationships among the variables in the data.
With unsupervised learning, there is no feedback based on the prediction results.

### Example:
Clustering: Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.
Non-clustering: The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).

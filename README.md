# Options-Price-Prediction-Using-Decision-Trees

# Objective: In this repository, we will create a trading strategy by using a decision tree classifier on a Nifty options data set by learning the decision rules from the training data set and use this decision tree in the test data set to predict whether the option price will go up (+1) or go down (-1) after one day and take trading positions.

# Background 

Decision Trees are a type of Supervised Machine Learning (that is you explain what the input is and what the corresponding output is in the training data) since the training dataset is labeled and we know that the option price willl either go up or go down. In this supervised machine learning, the data is continuously split according to a certain parameter. The tree can be explained by two entities, namely decision nodes and leaves. The leaves are the decisions or the final outcomes. And the decision nodes are where the data is split. In a decision tree, each root node represents the predictor variable, and a split point on that variable. While each leaf node of the tree contains an output variable. Once a decision tree is created, it can be navigated with a new data following each branch with the splits until a final prediction is made. Regarding the inputs, we can use the implied volatility and greeks such as delta, gamma, theta, and vega as inputs for predicting the direction of the option price. i.e. Consider the example of only using the implied volatility is high, the option price worths more so it is an incentive to sell the option. The decision tree classifier helps to determine the threshold value at which the implied volatility is considered high and we should sell the option.


# Methodology of the strategy 
  1. Define predictor variables
  2. Split the data into train and test dataset
  3. Create a decision tree classifier using the test data
  4. Compute the accuracy of the decision tree classifier
  5. Plot the performance of the classifier in the test data






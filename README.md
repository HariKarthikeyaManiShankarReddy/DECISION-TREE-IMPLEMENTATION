# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: CHENNAREDDY HARI KARTHIKEYA

*INTERN ID*: CT06DL832

*DOMAIN*: MACHINE LEARNING 

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

DESCRIPTION:

A Decision Tree is a Supervised Machine Learning Algorithm used for classification and regression tasks. It models decisions and their possible cmsequences as a tree like structure made up of nodes and branches.

A Decision Tree Classifier splits data into subsets based on the value od input features. Each internal node represents o decison or a feature, each branch represents the outcome of the decison and each leaf node represents a final class label. 

Decision Trees are used when the data is clearly seperable and it is easy to explain. Feature interactions are non_linear or complex.

These Decision Trees are manily used in Medical diagnosis, Credit scoring, Marketing, Fraud detection, Spam email detection.

There are mainly two measures used for the decision tree classifier:
1. Gini Impurity
2. Entropy

Gini Impurity:
  It is used in CART(Classification Regression Trees). Gini measures how often a randomly chosen sample would be incorrectly calssified if it were labeled randomly based on class distribution.
  The formula used to calculate is :
  [Gini=1-sigma (1 to n)*Probability of class(Pi)]
  if Gini=0 the node is perfectly purity.
  Gini is faster to compute.
Entropy: 
  It is also one of the measure used in Decision trees. Entropy comes from Information theory it measures unpredictibility or disorder in a set.
  The fromula used for calculating Entropy is:
  [Entropy=-sigma(1 to n)probability of class(Pi)*log base2* probability of class(Pi)]
  if all examples are of the same class then entropy is 0
  It has more theoretical and uses information gain. 
*OUTPUT*:


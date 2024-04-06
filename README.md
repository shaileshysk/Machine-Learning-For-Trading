# Machine-Learning-For-Trading
Artificial Neural Networks

Artificial Neural Network (ANN) is a type of supervised machine learning. The name and the algorithm both are inspired by the human brain. Like neurons in our brains helps us process information similar to that node in ANN also helps to process information. An ANN aims to solve any specific problem in the same way as a human brain would. ANN consist of multiple nodes which mimic the biological neurons of a human brain. As they are connected through links, they interact by taking the data and performing operations on it and then passing it over to the other connected node.

K Nearest Neighbours (KNN)

K nearest neighbours (KNN) is one of the simplest algorithms used in machine learning. It is easy to understand and successful in many problems, including handwriting recognition and email classification.
KNN is a non-parametric technique used in regression and classification problems. Here we will discuss only KNN classification. Nearest Neighbours classification is a type of instance-based learning or non-generalized learning. It does not attempt to construct a general internal model but compares the new problem with instances seen in training.
The purpose of the K nearest neighbours (KNN) classification is to use such data in which the data points are separated into different classes to classify new data points based on similarity measures (e.g. distance function). A majority vote of its neighbours classifies the object. The object is assigned to the class which has the nearest neighbours. As you increase the number of nearest neighbours, the value of k or accuracy might increase, but computation costs also increase.

Logistic Regression

Linear regression is used to predict values of quantities as a linear function of the input values. When predicting a discrete variable, such as whether a grid of pixel intensities represents 0 or 1, we need to classify the input values. Logistic regression is a simple classification algorithm for learning to make such decisions. It is a model that is used when the dependent variable is categorical. A few cases where logistic regression can be used are mentioned below:
Image segmentation and categorization
Geographic image recognition
Handwriting recognition
Determining whether a person is depressed based on the words of his social media posts
Predicting the probability of a person voting for a candidate in an election
Logistic regression falls under supervised learning; it measures the relationship between the categorical dependent variable and one or more independent variables by estimating probabilities using a logistic/sigmoid function. Despite the name 'logistic regression', it is not used for machine learning regression problem where the task is to predict the real-valued output. It is a classification problem that is used to predict a binary outcome (1/0, -1/1, True/False) given a set of independent variables. Logistic regression is a bit similar to linear regression, or we can say it as a generalized linear model. In linear regression, we predict a real-valued output ' y' based on a weighted sum of input variables.

Random Forest
Random Forest, also called Random Decision Forest, is a method in machine learning capable of performing both regression and classification tasks. It is a type of ensemble learning that uses multiple learning algorithms for prediction.

Random Forest comprises of decision trees, which are graphs of decisions representing their course of action or statistical probability. These multiple trees are plotted to a single tree called the Classification and Regression (CART) Model. To classify an object based on its attributes, each tree gives a classification that is said to vote for that class. The forest then chooses the classification with the maximum number of votes. For regression, it considers the average of the outputs for different trees.

Working

It assumes the number of cases as N. Then, randomly but with replacement, the sample of these N cases is taken out, which will be the training set.
Considering M to be the input variables, a number m is selected such that m < M. The best split between m and M is used to split the node. The value of m is held constant as the trees are grown.
Each tree is grown as large as possible.
By aggregating the predictions of n trees (i.e., majority votes for classification, the average for regression), random forest predicts the new data.

Support Vector Machine

A support vector machine, or SVM, is a machine learning technique widely used in data analysis and pattern recognition. SVM is a supervised learning model, which analyses the data used for classification and regression analysis. A set of training examples is provided to the SVM algorithm, each belonging to one or the other categories. The algorithm builds a model that assigns new data (X to Y) into one of the categories that it had learnt about in the training phase.

Consider the plots shown below. The graph on the left indicates the training data in space, the black coloured rings belong to one class, and the hollow rings belong to the second class. The SVM algorithm creates a hyperplane that divides this dataset into two parts so that when new data appears in space (depending on the side on which it appears), it will be classified into one of the classes.

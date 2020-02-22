# Credit-Risk-Analyzer
# Background
Credit Card Analysis is a type of analysis performed by Banks to ensure that the person they are giving credit cards or loans to will not be a defaulter and thus not cause losses to the banks. A good model will predict with a good accuracy whether a given person will pay his dues on time or not. This step is very important for any banks because credit defaulters may cause huge losses to the banks.
Why do we need Machine Learning?
If past is any guide for predicting future events, credit risk prediction by Machine Learning is an excellent technique for credit risk management. Prediction models are developed from past historical records of credit loans, containing financial, demographic, psychographic, geographic information, etc. From the past credit information, predictive models can learn patterns of different credit default/delinquency ratios, and can be used to predict risk levels of future credit loans. It is important to note that statistical process requires a substantially large number of past historical records (or customer loans) containing useful information. Useful information is something that can be a factor that differentially affects credit default/delinquency ratios.                                                                                                                 

# Objective
To create a Machine Learning model that will successfully depict whether a given person will default his credit card or not   

# Python Modules Used

1.	Scikit-learn (sklearn)
a.	DecisionTreeClassifier
b.	train_test_split
c.	accuracy_score
2.	Matplotlib
3.	Pandas
4.	NumPy



# Algorithm used

# Decision Tree
A decision tree is a decision support tool that uses a tree-like graph or model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.
A decision tree is a flowchart-like structure in which each internal node represents a “test” on an attribute (e.g. whether a coin flip comes up heads or tails), each branch represents the outcome of the test, and each leaf node represents a class label (decision taken after computing all attributes). The paths from root to leaf represent classification rules.
There are three commonly used impurity measures used in binary decision trees: Entropy, Gini index, and Classification Error.
Entropy (a way to measure impurity):
Entropy=−Sum (p * log2p) 

Gini index (a criterion to minimize the probability of misclassification):
Gini=1−Sum (p * p)

Classification Error:
ClassificationError=1−max(p)
where p is the probability of classes.



# DecisionTreeImplementation-MachineLearning
A decision tree project typically starts with a dataset containing input features and corresponding target labels or values. The goal of the project is to build a decision tree model that can make predictions or decisions based on the input features.

For Iris dataset the task is to print steps for every split in the decision tree.

The Project is divided in 2 parts -
1. Print the Decision tree steps as specified in the example below.
2. Decision Tree Implementation:  Building actual decision tree for the dataset and then printing it.

Dataset: Iris dataset.

Implementation: Consider the decision tree for OR below:

![image](https://github.com/aniketajagtap/DecisionTreeImplementation-CodingNinjas/assets/75877119/23fe413e-e465-4e5b-adfe-4017ed929e5e)

Expected Output:\
\
Level  0\
Count of  0(False)  =  1\
Count of  1(True)  =  3\
Current Entropy  is =  0.811278124459\
Splitting on feature  X1  with gain ratio  0.311278124459\
\
Level  1\
Count of  0  =  1\
Count of  1  =  1\
Current Entropy is =  1.0\
Splitting on feature  X2  with gain ratio  1.0\
\
Level  2\
Count of  0  =  1\
Current Entropy  is =  0.0\
Reached leaf Node\
\
Level  2\
Count of  1  =  1\
Current Entropy  is =  0.0\
Reached leaf Node\
\
Level  1\
Count of  1  =  2\
Current Entropy  is =  0.0\
Reached leaf Node

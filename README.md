# Project-Capstone

In this notebook we use the dataset about past loans , do feature engineering and implement the classification algorithms namely - KNN, DecisionTree,SVM and Logistic Regression. Also we find the best model based on evaluation metrics namely - jaccard index, F1 Score and LogLoss.

We load a dataset using Pandas library. This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

<img width="725" alt="Screen Shot 2023-10-30 at 2 48 02 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/c391cdec-89cd-4942-8808-fe7c7ae37e11">

Data Preprocessing:

260 people have paid off the loan on time while 86 have gone into collection. Lets plot some columns to underestand data better:

<img width="449" alt="Screen Shot 2023-10-30 at 2 35 31 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/e43be129-e067-4074-a9db-505a65b5238e">
<img width="449" alt="Screen Shot 2023-10-30 at 2 35 46 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/2c8a80d0-4cb1-4fae-ad07-716864391a17">

Lets look at the day of the week people get the loan:

<img width="471" alt="Screen Shot 2023-10-30 at 2 52 24 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/a409840e-fedf-4076-92be-f7d91808a5dc">

One hot Encoding :

<img width="1034" alt="Screen Shot 2023-10-30 at 2 34 41 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/f5bfe027-e26c-4fc0-8d1e-69d971a9da85">

Classification :

1. KNN -The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another.

2. Decision Trees- A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

3. SVM - Support vector machines (SVMs) are a set of supervised learning methods used for classification, regression and outliers detection.SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable.

4. Logistic Regression - Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.

Evaluation Metrics:

<img width="501" alt="Screen Shot 2023-10-30 at 2 59 58 PM" src="https://github.com/aditii02/Project-Capstone/assets/38829128/da404e05-2dec-4ca2-8db1-8151a7d934e9">




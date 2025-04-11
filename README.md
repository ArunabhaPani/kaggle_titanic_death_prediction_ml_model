# kaggle_titanic_death_prediction_ml_model
The above model has been created by using the titanic dataset present in the kaggle website and has been constructed by using eda on the titanic dataset and obtaining best possible by outcome with the help of implementation of various machine learning models like logistic regression, XGB Classifier, random forest classifier, decision tree classifier, voting classifier, Gaussian Naive-Bias,  etc.

Dataset Description
Overview
The data has been split into two groups:

train.csv – the training set

test.csv – the test set

The training set should be used to build your machine learning models.
For the training set, we provide the outcome (also known as the ground truth) for each passenger.
Your model will be based on “features” like passengers’ gender and class.
You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data.
For the test set, we do not provide the ground truth.
It is your job to predict these outcomes.

For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include:

gender_submission.csv – a set of predictions that assumes all and only female passengers survived.
This serves as an example of what a submission file should look like.

Data Dictionary
Variable	Definition	Key
survival	Survival	0 = No, 1 = Yes
pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd
sex	Sex	
age	Age in years	
sibsp	Number of siblings / spouses aboard the Titanic	
parch	Number of parents / children aboard the Titanic	
ticket	Ticket number	
fare	Passenger fare	
cabin	Cabin number	
embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton
Variable Notes
pclass: A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower

age:

Age is fractional if less than 1

If the age is estimated, it appears in the form of xx.5

sibsp:

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

parch:

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children travelled only with a nanny, so parch = 0 for them

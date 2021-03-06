# Regression
<p>Data on two variables recorded simultaneously for a group of individuals are called bivariate data. Examples of bivariate data are heights and weights of the students in a class, the rainfall and the yield of paddy in a state for several consecutive years, etc.</p>

<p>When we have bivariate data, we can, no doubt, consider the values of each variable separately to know the different measures like the mean and standard deviation of the variable; but here we are mainly concerned with two other problems.</p>
Firstly, we want to study the nature and extent of association, if any, between the variables. Secondly, if the variables are found to be associated we express one of them (regarded as the dependent variable) as a mathematical function of the other (considered as an independent variable), so that we can predict the value of the dependent variable when the value of the independent variable is known. The first problem is called correlation analysis and the second regression analysis. 
<br>
### What is Linear Regression?
To find the relationship between continuous correlated variables we use linear regression. Linear regression looks for a statistical  relationship between a set of correlated values. The representation is a linear equation that combines a specific set of input values (x) the solution to which is the predicted output for that set of input values (y). As such, both the input values (x) and the output value are numeric. When there is a single input variable (x), the method is referred to as simple linear regression. When there are multiple input variables,the method is referred to as multiple linear regression.
<br>

##### In contrast to the frequentist approach, Bayesian Linear Regression is also coded here. 
Link to my [Medium Blog](https://medium.com/@rajwritanath/bayesian-linear-regression-40f167b73e7a) on "Bayesian Linear Regression ".

### What is Polynomial Regression?
Linear Regression works on data where the dependent and independent variable have a linear relationship. But in cases where the data do not have a linear relationship and instead possess a rather complex relationship, then Polynomial Regression is used.

Polynomial Regression is a form of linear regression in which the relationship between the independent variable x and dependent variable y is modeled as an nth degree polynomial. Polynomial regression fits a nonlinear relationship between the value of x and the corresponding conditional mean of y, denoted E(y |x).

Link to my [Medium Blog](https://medium.com/@rajwritanath/linear-regression-using-normal-equations-3c972cb77c74) on "Linear Regression Using Normal Equations and Polynomial Regression".

### What is Logistic Regression?
Logistic Regression is an example of a classification algorithm which is used to find a relationship between features and probability of a particular outcome. The term "Logistic" is taken from the Logit function that is used in this method of classification.
Logistic Regression is tremendously useful in medical diagnosis given some specific symptoms and parameters. Like for example, logistic regression is used to detect early stages of breast cancer given certain parameters like age, past history, genetic factors, etc. 
<p>The name 'Logistic Regression', comes from it's underlying technique which is quite the same as Linear Regression. Like all regression analysis, Logistic regression is an example of predictive analysis. However unlike regular regression, the outcome calculates the predicted probability of mutually exclusive event occurring based on multiple external factors.
It can thus be considered as a special case of linear regression where the target variable is categorical in nature. Linear regression has a considerable effect on outliers. To avoid this problem, log-odds function or logit function is used. It uses a log of odds as the dependent variable. Logistic Regression predicts the probability of occurrence of a binary event utilizing a logit function.


As a small working example of Logistic Regression I have also worked on detecting malignancy of Breast Cancer based on the dataset of  [UCI Wisconsin](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)).
<br>
Link to my [Medium Blog](https://medium.com/@rajwritanath/logistic-regression-the-the-e8ed646e6a29) on "Logistic Regression".

# machine_learning_practice

<h2> <b> Simple Linear regression formula.. </b> </h2>
Y= a + bX 

Where..
<br/> Y – is the dependent variable
<br/> X – is the independent (explanatory) variable
<br/> a – is the intercept
<br/> b – is the slope
<br/> ∈ – and is the residual (error)

a= (Σy)(Σx2) - (Σx)(Σxy)/ n(Σx2) - (Σx)2

b= n (Σxy) - (Σx)(Σy) /n(Σx2) - (Σx)2

<h2><b> Logistic Regression </b></h2>

Logistic regression is basically a supervised classification algorithm. In a classification problem, the target variable(or output), y, can take only discrete values for given set of features(or inputs), X.

<b> Sigmoid Function : <b/>
The sigmoid function, also called logistic function gives an ‘S’ shaped curve that can take any real-valued number and map it into a value between 0 and 1. If the curve goes to positive infinity, y predicted will become 1, and if the curve goes to negative infinity, y predicted will become 0. If the output of the sigmoid function is more than 0.5, we can classify the outcome as 1 or YES, and if it is less than 0.5, we can classify it as 0 or NO. The outputcannotFor example: If the output is 0.75, we can say in terms of probability as: There is a 75 percent chance that patient will suffer from cancer.
  
<b> Types of Logistic Regression: </b>

Binary Logistic Regression: The target variable has only two possible outcomes such as Spam or Not Spam, Cancer or No Cancer.
<br />
Multinomial Logistic Regression: The target variable has three or more nominal categories such as predicting the type of Wine.
<br />
Ordinal Logistic Regression: the target variable has three or more ordinal categories such as restaurant or product rating from 1 to 5.
<br />

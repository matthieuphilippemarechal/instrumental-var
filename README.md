# instrumental-var

This is a new estimator, the associated article will be submitted soon. 

In the part without intercept, we assume that y=1 if beta X +u >0, y=0 else, where beta is a parameter that we want to estimate, X is an explanatory variable and u 
is the error term which has a standard normal distribution. We assume that X and u are not independant, which means that X is an endogenous variable. We so use an 
instrumental variable W related with X by the relation X=alpha * W + eta where eta has a normal distribution with mean value equal to zero. 

In our theorical reasearch, we have found a function f which satisfies beta = f(E[X*y],E[W*y]), so estimating these expected values, we can estimate beta.

The case without intercept is when y=1 if beta0 +beta1 X +u >0, y=0 else. In this case we found a function g such that (beta0,beta1)=f(E[y],E[X*y],E[W*y]).

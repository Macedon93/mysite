+++ 
date = "2020-04-04"
title = "Blog Addition"
description = "First addition to see if the blog mechanism."
series = ["Getting Started", "Hugo"]
+++

Table of Contents
=================

Statistical Learning is a subset of statistics, focused on supervised and unsupervised learning techniques.
-In essence statistical learning refers to a set of approaches for estimating f. In this chapter we outline some key theoretical concepts that arise in estimating f, as well as tools for inferencing. 

	- Why estimate f? There are two main reasons
	- Prediction: Inputs x are readily available, but the output y cant be easily found.  (Find the output Y). The focus of this book is on techniques for estimating f with the aim of minimizing the reducible error. 
	- Irreducible error always provides an upper bound while estimating and is almost always unknown.
	- Inference: Which prediction are associated with the response? What is the relationship between the response and the prediction?
	- Can the relationship between Y and each prediction be summarized by a linear equation?  Inferencing main point is that it gives details to the relationship.  

You can model for prediction  or model for inference 

Statistical learning as subset of statistics, focused on supervised and unsupervised learning techniques. 

More complex data models increase the amount of noise that our model can pick up. 

Most models for prediction can be found by using parametric and non-parametric methods. 

Parametric Methods 
	- Parametric methods involve a two-step model-based approach.
1.) First we make an assumption about the functional form or shape of F. One assumption is that f may be a linear model . Once we have assumed that f is linear , the problem of estimating f is greatly simplified. Instead of having to estimate an arbitrary  p-dimensional function f, one only has to determine the p+1 coefficients. (p being the number of variables)

2.)After a model has been selected, we need a procedure that uses training data to fit or  train the model. Common method of finding the correct parameters in  a linear model is to estimate least squares and minimize a cost/(loss) function. 
	- This model based approach just described is referred to as parametric; it reduces the problem of estimating f down to estimating a set of parameters.


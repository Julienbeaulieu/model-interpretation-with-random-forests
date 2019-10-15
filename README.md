In this notebook I share four different ways of making predictions more interpretable in a business context using LGBM and Random Forest. The goal is to go beyond using a model solely to get the best possible predictions, and to focus on gaining insights that can be used by analysts and decision makers in order to change the behavior of how a company does business, marketing, how they sell their product, etc.

I use a common data set - [Teleco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) - because it is simple and illustrates a classic business problem about growth.  

I will dive into the following methods:
- [Feature Importance](#1.-Feature-Importance)
- [Tree interpreter](#2.-Tree-Interpreter)
- [Partial dependance](#3.-Partial-Dependance)
- [Confidence based on tree variance](#4.-Confidence-Based-on-Tree-Variance)

I will apply them to our dataset, explain what they are, their usecases, how they are calculated, and interpret all the results.  

These learnings are a summary of the material used in Fastai's course [Introduction to Machine Learning for Coders](http://course18.fast.ai/ml.html).   
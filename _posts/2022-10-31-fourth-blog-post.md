# My Fourth Blog Post

## Write up a brief discussion of how you would plan to determine variables to use in a regression model.  
 
Variable selection in regression is identifying the best subset among many variables to include in a model. It is arguably the hardest part of model
building. Many variable selection methods exist because they provide a solution to one of the most important problems in statistics. 

There are a lot of frequently used variable selection methods. Classical variable selection methods include forward selection, backward elimination, and stepwise selection, R-squared and All-possible Subsets. Modern variable selection methods including LASSO, SCAD and bridge estimator. In all stepwise selection methods including all subset selection, a stopping rule or selection criteria for inclusion or exclusion of variables need to be set. Generally, a standard significance level for hypothesis testing is used. However, other criteria are also frequently used as a stopping rule such as the AIC, BIC or Mallows’ Cp statistic.

It is extremely important to include appropriate variables in prediction modelling, as model’s performance largely depends on which variables are ultimately included in the model. Failure to include the proper variables in the model provides inaccurate results, and the model will fail to capture the true relation that exists in the data between the outcome and the selected variables. There are numerous occasions when prediction models are developed without following the proper steps or adopting the proper method of variable selection. Researchers need to be more aware of and cautious about these very important aspects of prediction modelling.


## What variable selection techniques do you prefer and why?

Finding the best possible subset of variables to put in a model has been a frustrating exercise. Many variable selection methods exist. Many statisticians know them, but few know they produce poorly performing models. The resulting variable selection methods are a miscarriage of statistics because they are developed by debasing sound statistical theory to a misguided pseudotheoretical foundation.

Some researcher have then sought to present a better solution to variable selection in regression: the Natural Seven-step Cycle of Statistical Modeling and Analysis. He feel that newcomers to Tukey's EDA need the Seven-step Cycle introduced within the narrative of Tukey's analytic philosophy. 

Some researcher recommend that you use a criterion-based method. Criterion-based methods typically involve a wider search and compare models in a preferable manner. Stepwise methods use a restricted search through the space of potential models and use a dubious hypothesis testing based method for choosing between models. 

In sum, I would say if samples are not too small and if applied with care, variable selection methods may reduce the MSE of regression coefficients and predictions by separating irrelevant information from a model. In predictive research, variable selection may improve the accuracy of the predictions, but background knowledge can also be incorporated, going as far as updating the coefficients of an existing model with new data, and employing variable selection methods to assess that coefficients to update. Descriptive models are perhaps the most frequent type of models estimated in life sciences, and here variable selection may help to obtain interpretable and practically applicable models. 

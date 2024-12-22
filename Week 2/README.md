# Week 2 Journal Carmen Coronas (721687)

## 02_Uncertainty-week2.Rmd
This is a new Rmd for the second part of 2. Uncertainty. 
  ### General tasks
  - Replicate browse data example.
  - Replicate semiconductor example for BH algorithm. 
  - Investigate both datasets. 
  
  ### New findings: Experiments: 
  - BH algorithm lowering q to 0.01. Decrease in the threshold results in less non-zero coefficients (flatter line). 

## 03_Regression-week2.Rmd
  ### General tasks
  - Regression
  - Coefficient interpretation
  - Understand how regression in R works (matrices)
  - Relevel dataset and regressions
  
  ### Code related with spam dataset
  - New predictions
  - New coefficient interpretations
  - Deviance, explanation
  
## 04_Regularization-week2.Rmd
  ### General tasks
  - Replicate KFold example
  - Replicate Forward Stepwise Regression
  - Replicate Lasso and Lasso KFold CV
  - Replicate AIC and AICc
  - Experiments: KFold and Lasso-Ridge-Elastic Net


  ### Experiment: KFold with K=5
  - Replicate KFold example with 5 folds instead of 10: worse average OOS R2 = worse goodness of fit from this method.

  ### Experiment: Comparison Ridge, Lasso and Elastic Net using glmnet. 
  - Elastic net more lenient than Lasso for smaller coefficients. 
  - Resulted in different optimal values of lambda and different decisions regarding dropped coefficients. 
  - Graphs can be found in Rdm. 
  - Different values of alpha to adjust Ridge and Elastic Net. 

  ### Issues: 
We try CV KFold with median(y) instead of mean(y) for null deviance when computing R2 and we obtain an error due to ylim = ylim (need finite 'ylim' values). 







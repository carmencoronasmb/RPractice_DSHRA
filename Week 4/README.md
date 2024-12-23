# Week 4 Journal Carmen Coronas (721687)

  ### General tasks
  - Analyze consumer demand and price elasticity using linear regression models.
  - Estimate the effects of state-specific controls and trends on crime data.
  - Prepare and process datasets for orthogonal machine learning (ML) analysis.
  
## 06_Controls_part01.Rmd

   ### General tasks
  - Estimate consumer demand and price elasticity using regression models.
  - Analyze the impact of state-level controls on crime data.
  - Prepare datasets and implement orthogonal machine learning techniques.
  
  ### Consumer Demand Analysis
  - Modeled sales as a function of price and brand using linear regression.
  - Analyzed residuals to improve model precision.

  ### Crime Data Analysis:
  - Examined relationships between abortion rates and crime trends (1985-1997).
  - Incorporated state and time interactions as controls.

  ### Orthogonal ML:
  - Developed custom ML functions to address endogeneity and improve treatment effect estimations.
  
## 06_Controls_part02.Rmd

  ### General tasks
  - Prepare datasets with control variables for causal inference.
  - Implement orthogonal machine learning (ML) to analyze treatment effects.
  
  ### Data Preparation:
  - Processed data on abortion rates, crime trends, and control variables (e.g., income, gun laws).
  - Created interaction terms for state and time using sparse.model.matrix.
  
  ### Orthogonal ML:
  - Defined functions for variable selection (dreg, yreg) using cv.gamlr. 
  - Developed an orthogonal ML pipeline (orthoLTE) to estimate treatment effects while controlling for confounders.
  
  ### Insights:
  - Orthogonal ML isolates residual variations, improving causal inference and interpretability of results.
  
## Note
These last two code blocks do not leave much room for experimentation. Therefore, I have primarily focused on understanding 
the code and interpreting the results in detail.
  
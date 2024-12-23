# Week 3 Journal Carmen Coronas (721687)

## 05_Regularization Carmen Coronas (721687)

  ### General tasks
  - Analyze the KNN algorithm for classification.
  - Explore overlaps in data and challenges in prediction.
  - Experiment with k values in KNN.
  - Classification example using German Credit Data.
  
  ### KNN Algorithm
  - Dataset: fgl from the MASS library (214 observations, 9 variables).
  - Variables describe glass composition; type of glass is the class label.
  - Objective: Predict glass type based on composition.
  - Data scaling: Used scale() to normalize variables (mean = 0, SD = 1).
  - Experimented with different k values: 1, 2, 3, 5, and 8.
  - Results vary with each run due to random sampling.
  - Highlighted overlaps in data visualizations complicating predictions (e.g., Ba is predictive).

  ### German Credit Data
  - Replicated example from class. Understood. issue with real world data when used incorrectly. 
  - Applied classification techniques to a real-world dataset.
  - Investigated predictive performance and challenges in modeling.
  
  ### Experiment ROC curve
  - Try different package to obtain ROC curve
  - Issue related with axis: R represents specificity and sensitivity instead of sensitivity and (1-specificity).
  - Finally, I found Roc.C source in Taddy's repo.  
  - I try with different threholds and classification rules. 
  
  ### Issues
  - KNN: Results are highly sensitive to sample selection and k values.
  - Challenges with overlapping data distributions that impact model accuracy.

 ### Technical issue when knitting this week because of source(Roc.C). 

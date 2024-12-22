# Week 1 Journal Carmen Coronas (721687)

## 01_Introduction_24_25.Rmd
This first file heavily relies on an explaination from the slides for the course. As it was introductory, I was getting in touch my RMarkdown. 
  ### General tasks
  - Updated R and R-Studio to the latests versions
  - Cannot render the slides because there are some issues with some packages. 
  - Investigated main libraries and packages in the Code
  - Learned about `apply()` function.
  - Installed required packages: `rmarkdown`, `htmltools`.

  ### Code related with survey_responses.csv
  - Investigated the dataset
  - Main stats
  - Types of variables (learnt the type of avriables from the apply() command. 
  - Barplot to visualize some frequencies from the variables and their proportions.
  - Run the regression proposed

  ### New findings: 
  - Experimented with data visualization using `ggplot2`.
  - Discovered the difference between `sapply()` and `lapply()`.
  
  
## 02_Uncertainty-week1.Rmd
I created a new Rmd, different from the slides to customize my own chunks and implement my experiments.

  ### General tasks
    - Tried to visualize slides. 
    - Investigated main libraries and packages in the code
    
  ### Code for browse.csv
    - Open the dataset and investigate it: dimension, variables.
    - Performed bootstrap sample (line by line explaination)
    - Experimenting with bootstrap without regression
    - Performed histogram (ChatGPT help!)
    - Performed bootstrap regression (line by line explaination)
    - Check covariances and SD. 
    
  ### New findings: experimenting with bootstrap algorithm. 
	- When carried out without replacement, standard  deviation = 0!
	- Bootstrap with 1000 iterations carried out twice provides slightly different results. 
	- Bootstrap with 500 iterations is faster and provide less accurate estimations. Still, they do not differ substantially. 

Bootstrap is useful in low dimensional data. Limitation: depends too much on the sample size and quality.
 

    
    
    
    
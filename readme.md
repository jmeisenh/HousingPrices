---
title: "Housing Prices NYC DSA Project"
author: "Justin Meisenhelter, Vinod Chugani"
date: "4/4/2022"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# Housing Prices Modeling  


## Initial Goals (timeline)

### Week 1 (April 3rd - April 9th)
1. Initial Data Cleanup    
    + Remove all NA rows, save new CSV for test and train  
    + Inpute mean of all numerical columns, replace NA's. for test and train  
2. Prepare for Modeling  
    + Correlation Plot for predictor variables  

    + Initial Feature Selection  
3. Initial Modeling  
   + MLR model fit on both cleaned test datasets and relevant scoring metrics  
   + Ridge, Lasso, ElasticNet fits on both cleaned datasets  

### Week 2  
1. Feature Selection  
2. MLR and elastic net model, some hyperparamter tuning  



## Progress  
### Week 1  
+ April 5th - Cleaned all NA values in test csv
+ April 6th - Some EDA , correlation plot
+ April 8th - Initial Feature selection

### Week 2
+ April 12th - Initial Feature Selection completed  and Train Test split   
+ MLR Model $R^2 = .006$  
+ ElasticNet Model $R^2 = 0.86$ (That's improvement)  
+ April 16th - Tries two more version of feature engineering to little to no success  


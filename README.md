# House-Price
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a     
  higher price
-Understanding which variables are significant in predicting the price of a house
-How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimum lambda value in case of Ridge and Lasso is as follows:- 
    Ridge – 10 
    Lasso – 0.5 
  The Mean Squared Error in case of Ridge and Lasso are: 
    • Ridge - 0.0018396090787924262 
    • Lasso - 0.0018634152629407766 
  The Mean Squared Error of both the models are almost same. Since Lasso helps in feature 
  reduction (as the coefficient value of some of the features become zero), Lasso has a better 
  edge over Ridge and should be used as the final model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas as pd
- matplotlib.pyplot as plt
- seaborn as sns
- numpy as np
- from scipy.stats import norm
- from sklearn.preprocessing import StandardScaler
- from scipy import stats
- from sklearn.model_selection import train_test_split
- from sklearn.linear_model import LinearRegression,Lasso, Ridge
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by deepak kuamr jain - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

# README: SAT Scores Lab 6 Model

## Data

This weeks’s data is about creating model from SAT Scores and using difference features such as BIC, AIC, and adjusted R2 to determine what is the ideal model to predict SAT scores in a linear model. The dataset is part of Sleuth3 packages which is case 1201

The dataset in this lab contains the SAT score (out of 1600) and other variables that may be associated with SAT performance for each of the 50 states in the U.S. The data are based on test takers for the 1982 exam.

    - SAT: average total SAT score
    - State: U.S. State
    - Takers: percentage of high school seniors who took exam
    - Income: median income of families of test-takers ($ hundreds)
    - Years: average number of years test-takers had formal education in social sciences, natural sciences, and humanities
    - Public: percentage of test-takers who attended public high schools
    - Expend: total state expenditure on high schools ($ hundreds per student)
    - Rank: median percentile rank of test-takers within their high school classes

## Lab

The lab wants us to create a linear model that predicts the SAT score based on six covariates or variables: Takers, Income, Year, Public, Expend, Rank. Where it askes a few questions on how to decide on model selection using various indicators such as AIC, BIC, and adjusted R2. It has follow up questions on how to find outliers that may affect the model's accuracy and to see if other covariates are affecting each other within the dataset.

# LearnML_PracticalApp3
Comparing classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines)

#### Business Question  
Find a classification model that will most accurately predict the likelihood of converting a marketing outreach (marketing call) into a term loan subscription  

#### Outline of project

- [Link to notebook 1]()

Following techniques are used in the analysis: 
1. Performed ***EDA and data transformation*** before training the models
2. Transformed the data attributes as required. **Encoded categorical variables and scaled numeric variables**
3. Created training and test datasets and **built a baseline model** to establish baseline accuracy score and AUC score
4. Built simple **k-nearest neighbors, logistic regression, decision trees, and support vector machines models** and compared their performance
5. Performed **hyperparameter tuning** to find the best model with the best attributes 


#### Results
Logistic regression proved to be the best model based on AUC and Accuracy Scores. It is able to predict the likelihood of converting a marketing outreach into a term loan subscription with AUC of .79 (baseline AUC was 0.49) and test accurary of .83 (base line accuracy was .79) 





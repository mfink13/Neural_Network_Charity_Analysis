# Neural_Network_Charity_Analysis

## Overview
  The purpose of this project was to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.  The client would be able to continuously use this machine learning model in the future.
  
## Results

### Data Preprocessing
  - What variable(s) are considered the target(s) for your model?
   
     The variable that was used as the target was the columns "IS_SUCCESSFUL"
    
  - What variable(s) are considered to be the features for your model?
   
     The variables used as features were all of the other columns in the cleaned dataset "application_df", inclduing APPLICATION_TYPE,	AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS, and	ASK_AMT.
    
  - What variable(s) are neither targets nor features, and should be removed from the input data?
   
    The variables that were initally removed from the input data were "EIN" and "Name".

### Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    I choose to start by increasing each by 40.  Therefore I had 83 input features, 120 first hidden layers and 70 second hidden layers.  I did this to try to give the model more data to interpret to hopefully increase the accuracy.
    
  - Were you able to achieve the target model performance?
   
     Unfortunetly, I wasn't able to achieve the target model performance.  I had an issue that I was not able to solve - my kernel died once I tried to optimize and I wasn't able to revive it.  I tried to recreate the whole project in a new repository, but kept running into a dead kernel. I also tried to delete my H5 file, as google said that may be the problem, but that did not fix the problem either.  Since ther kernel died, I was never able to recreate my H5 file either, so that is why it is missing.
    
  - What steps did you take to try and increase model performance?
   
     Beyond changing the number of neurons and layers, I also dropped the columns that I considered insignificant, "SPECIAL_CONSIDERATIONS_N" and "SPECIAL_CONSIDERATIONS_Y" to help clean the dataset further. I also adjusted the activation features. 
    

## Summary 
Due to my technical difficulties, I was not able to properly optimize my learning model or learn from it.  A potential recommendation of a different model the solve this classification problem would be random forest. I would suggest random forest as it provides higher accuracy through cross validation. Random forest classifier can handle missing values and maintain the accuracy of a large proportion of data.

# Adult Income

 This data describes the features related to adult incomes. We compare the difference between someone who pursued higher education vs someone who didn't and what that outcome was.

## Rosa Rocha

<p align = "center"> 
  <img src = "https://github.com/RosaR02/Car-and-Adult-Income/blob/main/images/income.png">
</p>

Who is your stakeholder, and what problem are you solving for them? The Department of Education to show areas of focus for improvement of outcomes.


## DATA CLEANING - To prepare this data, the data was cleaned, and the following processes were performed:
  - Duplicate rows were dropped
  - Rows and Columns (48842, 15)
  - Identify missing values
  - concatenate and fix any inconsistent categories of data

### Visualizations
    - A seaborn countplot and histogram visualized for numeric datatype column. 
    - Also, a barplot was visualized for categorical column. 
    - This gave a good baseline for the numeric and categorical columns.
    

<p align = "center"> 
  <img src = "https://github.com/RosaR02/Car-and-Adult-Income/blob/main/images/race-histplot.png">
</p>

The majority of employees are white compared to any other race.

<p align = "center">
   <img src = "https://github.com/RosaR02/Car-and-Adult-Income/blob/main/images/race-income.png">  
</p>
This visualization shows the white race as the majority making 50k or less equally the same race makes 50k or more compared to other races. Virutally zero Others and Amer-Indian-Eskimo make 50k or more.


<p align = "center">
   <img src = "https://github.com/RosaR02/Car-and-Adult-Income/blob/main/images/income-education.png"> 

 Here you can see a clear correlation between income and eduation. Very few people with a high school education (not grad) can still make over 50k.


 ### Maching Learning Using the Following Models:
    - Logistic Regression Model
    - Random Forest Classifier Model
    - KNN Classifier Model

    
    
## Models Evaluated & Results

<p align = "center">
   <img src = "https://github.com/RosaR02/Car-and-Adult-Income/blob/main/images/bestmodels.png"> 



- The Final Model Chosen was a Logistic Regression PCA Tuned Model.



## Recommendations

Model Performance

-  Given the results of the models after running with PCA I think Logistic Regression PCA Tuned performed slightly better than Random Forest therefore I would use this as my prediction model and suggest to my stakeholder. KNeighbors actually scored lower before using PCA but still lower than both other models.
  




## For Further Information

For any additional questions, please contact: 
- Rosa Rocha
- rosarocha0563@gmail.com

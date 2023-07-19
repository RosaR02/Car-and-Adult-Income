# Adult Income

 This data describes the features related to adult incomes.

## Rosa Rocha

## insert image

<p align = "center"> 
  <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/data%20dictionary.png">
</p>


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
  <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/countplot.png">
</p>

This histogram below shows the Medium Outlet Size has more sales than the other 2 Outlet Sizes.

<p align = "center">
   <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/Histplot.png">  
</p>

 ### Explanatory Data Analysis
    - To visualize the data for explantory purposes, two bargraphs were chosen and one linegraph was chosen.
    - The bargraphs were chosen to show how the categories compare to each other. 
    - Finally, a linegraph was chosen to show the outlet type. 


## Explanatory Visuals

<p align = "center">
    <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/barplot.png">
 </p>
 
 This barplot shows the top 5 highest selling items though slighly close by average:
  - Starchy Foods            2374.332773
  - Seafood                  2326.065928
  - Fruits and Vegetables    2289.009592
  - Snack Foods              2277.321739
  - Household                2258.784300
 
 <p align = "center">
    <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/lineplot.png">
 </p>


This lineplot shows that Supermarket type 3 has the most sales compared to the Grocery store which has the lowest of all.


 ### Maching Learning Using the Following Models:
    - Logistic Regression Model
    - Random Forest Classifier Model
    - KNN Classifier Model

    
    
## Models Evaluated & Results

- Logistic Regression PCA Tuned :

              precision    recall  f1-score   support

           0       0.93      0.78      0.85      8794
           1       0.56      0.82      0.67      2950

    accuracy                           0.79     11744
   macro avg       0.75      0.80      0.76     11744
weighted avg       0.84      0.79      0.80     11744Linear Regression Model (Testing Set):


- Random Forest PCA Tuned :

              precision    recall  f1-score   support

           0       0.93      0.78      0.85      8794
           1       0.56      0.81      0.66      2950

    accuracy                           0.79     11744
   macro avg       0.74      0.80      0.75     11744
weighted avg       0.83      0.79      0.80     11744Decision Tree Regressor Model (Testing Set):

- KN Tuned :

              precision    recall  f1-score   support

           0       0.91      0.73      0.81      8794
           1       0.49      0.79      0.61      2950

    accuracy                           0.74     11744
   macro avg       0.70      0.76      0.71     11744
weighted avg       0.81      0.74      0.76     11744




- The Final Model Chosen was a Logistic Regression PCA Tuned Model.



## Recommendations

Model Performance

-  Given the results of the models after running with PCA I think Logistic Regression PCA Tuned performed slightly better than Random Forest therefore I would use this as my prediction model and suggest to my stakeholder. KNeighbors actually scored lower before using PCA but still lower than both other models.
  




## For Further Information

For any additional questions, please contact: 
- Rosa Rocha
- rosarocha0563@gmail.com

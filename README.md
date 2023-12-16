# mobile_price" 
### Deployed link - 
https://cellphonepricerangeprediciton.streamlit.app/

# Cellphone_price_range_predction
- In this project we have to predict cellphone price range on the basis of given features.

---------------------------------------------------------------------


- During Datapreprocessing I found the corrupted value then i replace corrupted value by 0 using MEDIAN.
- And actually in Datapreprocessing during checking outliers I found outliers in front camera(fc) features then i haldle outliers by using IQR method.
---------------------------------------------------------------------
- Then I check Data distribution and i found skewness in front camera(fc), But it will not give much impact on target variable so I leave as well. 
-------------------------------------------------------------
- During Freature selection I used heatmap to check coorelation that how data is coorelated and I found pc vs fc and three_g vs four_g that is not highly coorelated. If there was correlation, above 85 to 90% then we would have drop it. 
--------------------------------------------------------------

## The Output feature column have multiclass feature so for this reason we have choosen this  problem statement as multiclass classification and then we use diffrent Algorithm to check the performance of the diffrent algorithm this can be checked using f1 score and comparing it down by with diffrent model accuracy, so  whichever model is showing highest accuracy score we have choosen that model for our prediction.

----------------------------------------------------------------------
###  I used diffrent ML algorithm
  - 1. Logistic Regression
  - 2. RandomForest Classifier
  - 3. SVM Classifier
  - 4. Decision Tree Classifier
  - 5. AdaBoostClassifier
  - 6. GradientBoosting Classifier
  - 7. XGB Classifier
  - 8. Naive Bayes Classifier
  - 9. KNeighborsClassifier
-----------------------------------------------------------------------

### Out of these Algorithm there is performed some algorithm better than other:

 - RandomForest Classifier
 - SVC Classifier
 - GradientBoosting Classifier
 - XGB Classifier
 ----------------------------------------------------------------
### After Hyperparameter Tuning some model has variation but still Random forest performing well before-and-after Hyperparameter Tuning
 
 - RandomForest Classifier
 
 
##### After Hyperparameter tuning I found that RandomForest Classifier giving well accuracy on data as compare to all model so We have choose this model for future prediction of cellphone price  that which type of feature in cellphone want really deserv for market trends.

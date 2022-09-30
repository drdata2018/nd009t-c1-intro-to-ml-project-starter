# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Ahmed Abdulkader

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: Well, i realized that the data were withoud analysis or feature engineering and i had to relace all negative values with zero to sumit kaggle.

### What was the top ranked model that performed?
TODO: WeightedEnsemble_L3 was the best 

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Actually  I divided the datetime in month, day, year and hour and it was usefull to transform the season and weather features to categorical

### How much better did your model preform after adding additional features and why do you think that is?
TODO: additional features can be good predictors to estimate the target value, in this case I decided to separate the date becuase it helps the model to analyse seasonality paterns in the data which can be usefull for a regression model

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: some configurations were usefull but others harmed the model performance

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: do more data analysis, and research in deep with  hyperparameters

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|hpo4|using_val_data|score|
|--|--|--|--|--|--|--|
|initial|defaults|presets='best_quality'|default|1.758410|
|add_features|defaultsdefaults|default|0.737108|
|hpo|defaults|defaults|scheduler: local, searcher: auto|0.474920|
|hpo2|time_limit = 600|presets='best_quality'|scheduler: local, searcher: auto|1.317800|


![Untitled](https://user-images.githubusercontent.com/37417270/193337890-ab3f37ea-28d5-43f5-ad8f-8638822e07c5.png)

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.
![index](https://user-images.githubusercontent.com/37417270/193337572-a24680f1-13b0-49d5-a8c7-68655549f673.png)




### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![2](https://user-images.githubusercontent.com/37417270/193337612-19d2cbb3-8de2-476f-a165-23071f325c6e.png)


## Summary
TODO : 
in this project I was able to apply all the concepts that were covered in this unit of the course, by using this skills I was able to develop a machine learning regression model by using the autogluon framework, at the end the results were good because the kaggle score of my model was close to the professional developers with years of experince.



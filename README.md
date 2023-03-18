## 2020-Election-Decision-Tree

Goal: Predict the political polarity of Massachusetts towns (ie wicked blue, medium blue, light blue, or red) and discover most important features

Data set: attached town_data.csv containing 75 facts about 350 Massachusetts towns and cities

Models used: Decision Tree, Random Forest, K-Nearest Neighbors, XGBoost


## Results

  ### Best Performing Model: Random Forest 
  
	Multiclass Peformance:
	
		Accuracy: 0.7571
		
		F1 Score: 0.7559
	
### Democrat vs Republican Binary Classification Performance:
	
		Accuracy: 0.9285
		
		F1 Score: 0.8387
  
### 10 Most important Features:

  ![Feaure Importances](https://github.com/eric1anderson/2020-Election-Decision-Tree/blob/main/images/feature_importance.png)


### Confusion Matrix of best model:

![Confusion Matrix](https://github.com/eric1anderson/2020-Election-Decision-Tree/blob/main/images/confusion_matrix.png)
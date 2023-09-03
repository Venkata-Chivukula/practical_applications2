Summary of the key findings- 

The modeling has idenfied the following key features that customers value in the used car - 
1. Number of cyclinders = 3
2. Hybrid Fuel Type
3. Gas Fuel type 
4. Title status parts only
This model can be deployment at various dealerships across the US to identify the key features that customers value most. This helps in identification of factors that drive the price of the car. 

### Final report
The modeling approach present here considered the business objectives and, with that in mind, looked at the data source and performed preprocessing to clean the data and make it usable. The data was analyzed to find the correlation between numerical, categorial features and the price of the car. Initial analysis indicated the cost of the car is positively correlated to type_pick_up and type_truck. It is negatively correlated with odometer value and car age. Intuitively, this makes sense; older cars have a lower price, and as a car ages, its odometer increases. The data was split into test and training datasets, the pipeline models were built and prediction errors was computed for various models. The best model was identified to be linear regression based on the lowest RMSE and MAE. The Grid Search CV was performed on the linear regression model to select the best hyperparameters, and the final feature importance was computed to identify the top 5 features that customers value most in a car. 

The main project file is practical_application_2.ipynb
The images of the plots generated are saved in image folder. 
The data source is stored in data folder. 

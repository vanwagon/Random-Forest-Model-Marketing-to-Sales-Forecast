# Random Forest Model - Marketing to Sales
 Random Forest Predictive Model to predict sales impact & outcomes given marketing spend.
 ***This is a professional project. Please be aware that all data has been randomized and masked for confidentiality.***
 
The model creates a separate decision tree for each product, allowing for customized predictions for individual product patterns. A loop iterates through each product and generates a forest for that product.


This model does not capture relationships between products. (i.e., lower inventory for X product does not mean people opt for Y product) Since we are doing 1 product at a time, we lose out on any shared patterns or relationships that might be observable
i.e., promotion for product X trickling down to product Y and vice versa

The model below will calculate each vehicle separately, and later aggregate them into a CSV file. The data is hot-encoded where each model has a column. It is binary where 1 is for that model, and 0 for not that model.

Feature importance is a metric that indicates how much each input variable (or feature) in a model contributes to the model's predictions. In simpler terms, it shows which factors are most influential in determining the outcome. If a feature has high importance, it means that it plays a significant role in predicting the target variable.

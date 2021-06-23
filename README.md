# Don't Get Kicked (Kaggle-R)

Data science project from Kaggle completed using R as part of school project.

### Overview

#### Problem Statement

One of the biggest challenges of an auto dealership purchasing a used car at an auto auction is the risk of that the vehicle might have serious issues that prevent it from being sold to customers. These unfortunate purchases are called "kicks." Kicked cars can be very costly to dealers after transportation cost, throw-away repair work, and market losses in reselling the vehicle.

The challenge of this problem is to predict if the car purchased at the Auction is a Kick (bad buy).

#### Approach

I started with with preprocessing data before predicting the target variable which is IsBadKick and spliting the data into training and testing groups. Then I conducted model fitting and implemented a logistic regression to model and fit the data. To quantify the models, I calculated accuracy with different cutoff values, F1 Score, Precision, Recall  which are a better measure for accuracy of a binary classification problem. I also implemented AUC(Area Under the Curve) to find the cutoff value. 
#### Result
The F1 score of the model has strength of 63.42352%.\
The AUC is 66.43968%.\
The best score after submitting challenge is 0.08085. 


|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/DontGetKicked-Kaggle-R/blob/main/Don-tGetKicked3_files/figure-gfm/unnamed-chunk-6-1.png?raw=true"> |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="https://github.com/WiroonB/DontGetKicked-Kaggle-R/blob/main/Don-tGetKicked3_files/figure-gfm/unnamed-chunk-11-1.png?raw=true"> |
|:-------------------------:|:-------------------------:|


#### Note

Because this dataset is imbalanced, AUC is a better measure for accuracy of a binary classification problem which is why it is included in model performance.
F1 score is also a better metric to evaluate the models.

Link to Kaggle Challenge
https://www.kaggle.com/c/DontGetKicked

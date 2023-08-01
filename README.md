# Clustering_Classification_NN

data: Bank telemarketing performance, target variable = "y" (yes/no); whether the person subscribed to a term deposit.
Divide dataset into 2 clusters, apply a neural network to one and a supervised classification algorithm to the other

1. Initial EDA to understand the dataset and identify relevant features (and remove irrelevant ones).
2. K-means clustering to split the dataset into 2 clusters, despite the ideal number of clusters being 4 (as shown in elbow method).
3. Test 3 models = Logistic regression, xgb boost, and random forest (evaluated prioritizing Recall and F1 score - case specific).
4. Neural network on second (and larger cluster) with the same objective of classification (similar evaluation criteria as point #3).
5. Conclusion = classification probability threshold ideally 0.3 as opposed to default of 0.5 gives best results.

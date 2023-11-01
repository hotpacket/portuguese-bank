# Portuguese Bank

We are creating a model to predict the success of a Portuguese bank's marketing campaign. The goal of the campaign is to convince customers to purchase bank deposit subsriptions. The model will attempt to identify customers with a greater likelihood of purchasing subscriptions.

To this end, we will try several classification models, namely K-Nearest Neighbors, Logistic Regression, Decision Trees, and Support Vector Machines. 

Our dataset comes from the UCI Machine Learning repository (https://archive.ics.uci.edu/ml/datasets/bank+marketing). 

## Summary of Findings

<img width="317" alt="image" src="https://github.com/hotpacket/portuguese-bank/assets/136177819/9aec1091-5abc-43a1-bb93-00b8d9b45dea">

Our most accurate classification model (and fastest to train) was the decision tree model, as seen in the chart above. By tuning hyperparameters, we were able to boost test accuracy slightly as shown below:

<img width="444" alt="image" src="https://github.com/hotpacket/portuguese-bank/assets/136177819/c90ae552-f69a-404f-a553-15ec859b1e98">

The following picture describes the decision tree (click picture to open and click again to enlarge):

![dtree_render](https://github.com/hotpacket/portuguese-bank/assets/136177819/4addda67-44ab-4760-9d96-5f19b332a263)







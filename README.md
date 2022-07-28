# timeseriesKaggle
Use machine learning to predict grocery sales
Datasets:https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data
The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as:
[\sqrt{ \frac{1}{n} \sum_{i=1}^n \left(\log (1 + \hat{y}_i) - \log (1 + y_i)\right)^2}]
where:

    𝑛

is the total number of instances,
𝑦̂ 𝑖
is the predicted value of the target for instance (i),
𝑦𝑖
is the actual value of the target for instance (i), and,
log
is the natural logarithm.

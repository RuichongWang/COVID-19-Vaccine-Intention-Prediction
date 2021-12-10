# Humana-Competition
Predicting the Likelihood of Receiving Vaccines Using an Ensembling of CatBoost and TabNet Approach

In this competition, we used the ensemble of TabNet and CatBoost. This is an already oversampled imbalanced dataset, 17% of the total sample are positive samples. In other words, the ratio of the number of positive samples to negative samples is 1:5. To solve this problem, we used methods that are similar to down-sampling. We randomly split all the negative samples into 5 parts and for each part, we combine it with all the positive samples.

<p align="middle">
  <img src="imgs/subdata.png" height="400"/>
</p>

We also added the result of Partial Dependence Plot (PDP), Individual Conditional Expectation (ICE) and Shapley Value to increase the model interpretive ability.

<p align="middle">
  <img src="imgs/interpretable_ml.jp2" height="200"/>
  <img src="imgs/interpretable_ml2.jp2" height="200"/>
  <img src="imgs/interpretable_ml5.jp2" height="200"/>
  <img src="imgs/interpretable_ml6.jp2" height="200"/>
  <img src="imgs/interpretable_ml7.jp2" height="200"/>
</p>

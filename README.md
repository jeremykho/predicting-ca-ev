## Statistical Models to Predict Electric Vehicle Ownership

<i> Note: File formats and structure based on submission requirements. </i>

### Abstract

The transition to electric vehicles seems to be inevitable and predictions are being made about when total adoption will happen. The reality is that EV adoption will span years and will require changes to policies and infrastructure. One problem is the lack of data related to EV adoption at this scale. However, looking to states that have higher adoption serves as a good start. In this project, I explore statistical methods to predict EV ownership among households in the near future. Due to its high adoption rate and availability of data from the 2017 National Household Travel Survey, California is the basis of the model. Because only 2.5% of California households own electric vehicles, Precision- Recall through the F1 Score was selected as the evaluation metric. After data preparation, the records were split into sets for training, validation, and testing. Three models were constructed: k-Nearest Neighbors, Random Forest, and Ridge Regression. To provide meaningful predictions, the threshold for classification was set as a dynamic parameter tuned through the validation set. In testing, kNN performed the worst with an F Score at 0.53, followed by Random Forest at 0.55, and Ridge at 0.57. The best precision and recall scores for predicting EV owners were at 14% and 22%, respectively, which are seen to be modest, considering that only 2.3% of the test set were actually owners. Although model predictions are better than random, improvements clearly need to be made. A prediction made in Texas with a six-fold increase in adoption can be used by analyzing which categories of households were false positives and would be most similar to EV owners, making them 'low-hanging fruit' for decision makers. Aside from the meager performance of the models, caveats include factors not included, such as state culture, politics, and incentives. Moreover, the data are a snapshot in time and do not incorporate the rate of adoption, change in price of vehicles, change in price of fuel, change in environmental policy, and so on.

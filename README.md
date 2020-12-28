# Credit_Risk_Analysis
The purpose of this analysis is to use machine learning algorithms to predict credit risk to help provide a quicker and more reliable loan experience. Hopefully, this analysis will provide a more accurate identification of good candidates for loans which will lead to low default rates.
##  Results
In this project, 4 algorithms were used: RandomOverSampler, SMOTE, ClusterCentroids and SMOTEENN.

---
* For the RandomOverSampler algorithms, I got a balanced accuracy score of 0.65,precision scores 0f 0.01 for the high risk and 1 for the low risk; recall score of 0.73 for high risk and 0.57 for low risk applications.

![RandomOverSampler](https://github.com/Elewekeadanma/Credit_Risk_Analysis/blob/main/RandomOverSampler.jpg)
---
* For the SMOTE algorithm, I got a balanced accuracy score of 0.66, precision scores of 0.01 for high risk and 1 for low risk; recall scores of 0.63 for high risk and 0.68 for low risk applications.

![SMOTE](https://github.com/Elewekeadanma/Credit_Risk_Analysis/blob/main/SMOTE.jpg)
---
* For the ClusterCentroids algorithm, I got a balanced accuracy score of 0.55; precision scores of 0.01 for high risk and 1 for low risk; recall scores of 0.68 for high risk and 0.41 for low risk applications.

![ClusterCentroids](https://github.com/Elewekeadanma/Credit_Risk_Analysis/blob/main/ClusterCentroids.jpg)
---
* For the SMOTEENN algorithm, I got a balanced accuracy score of 0.65; precision score of 0.01 for high risk and 1 for low risk; recall scores of 0.72 for high risk and 0.57 for low risk.
![SMOTEENN](https://github.com/Elewekeadanma/Credit_Risk_Analysis/blob/main/SMOTEENN.jpg)
##  Summary
For all the models, the precision for low risk application is high while the precision for high risk applications is low indicating a large number of false positives which indicates an unreliable classification.
The SMOTEENN and RandomOverSampler algorithms had better recall scores than the ClusterCentroids and SMOTE algoritms for high risk applications.Higher recall scores are indicative of a smaller number of false negatives. I would not recommend any of the algorithms but if I had to pick at least one, I will pick either the SMOTEENN or RandomOverSampler algorithm.
All the models may not be good at predicting high risk applications because they all had low accuracy scores.











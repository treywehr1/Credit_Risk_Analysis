# Credit Risk Analysis

## Overview of Analysis
A number of supervised machine learning models and methods were used to develop a process of evaluating credit worthiness and the important features available when assessing credit worthiness.

RandomOverSampler, SMOTE, SMOTEENN algorithms, BalancedRandomForests and EasyEnsembleClassifier classifiers were used to evaluate predicted results and their effectiveness.


## Results
 - The results of the RandomOverSampler algorithm resulted in a balanced accuracy score of 0.6146309649640125. 
 - The avg/total accuracy of the ROS was .99 and the avg/total precision was measured at .67.
 - The results of the SMOTE algorithm resulted in a balanced accuracy score of 0.6242501208448599. 
 - The avg/total accuracy of SMOTE was .99 and the avg/total precision was measured at .69.
 - The results of the ClusterCentroids algorithm resulted in a balanced accuracy score of 0.5152848567382999. 
 - The avg/total accuracy of the ClusterCentroids was .99 and the avg/total precision was measured at .44.
 - The results of the SMOTEENN algorithm resulted in a balanced accuracy score of 0.6455969261246168. 
 - The avg/total accuracy of the SMOTEENN was .99 and the avg/total precision was measured at .57.
 - The results of the BalancedRandomForestsClassifier resulted in a balanced accuracy score of 0.6951188648085522. 
 - The avg/total accuracy of the BRFC was .99 and the avg/total precision was measured at .93.
 - The results of the EasyEnsembleClassifier resulted in a balanced accuracy score of 0.8229539706914415. 
 - The avg/total accuracy of the BRFC was .99 and the avg/total precision was measured at .89.
 
 ![ROS](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/ROS.png)
 ![SMOTE](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
 ![ClusterCentroids](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)
 ![SMOTEENN](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)
 ![BRFC](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/BRFC.png)
 ![EEC](https://github.com/treywehr1/Credit_Risk_Analysis/blob/main/Resources/EEC.png)
 

## Summary
The results collected showed that there was very small differences in most of the ML procedures practiced. When looking at the first four algorithms, it seems that the SMOTE and SMOTEEN methods showed a higher overall effectiveness compared to the ROS and ClusterCentroids algorithms. There was a significant improvement in accuracy scores and avg/total precision when evaluating the performance of the final two models, the BRFC and the EEC, with the EEC showing the highest balanced accuracy score by far and a competitive precision of .89 in comparison to the BRFC's .93 precision score. The avg/total accuracy for all models sitting at .99 sends a red flag to the evaluator because this indicates that the low number and therefore imbalance of "high_risk" results has lead the model to be weak at predicting these outcomes, while at the same time being highly accurate in predicting "low_risk" outcomes.

Out of the 6 available models, the Easy Ensemble Classifier would be recommended for its balanced accuracy score and avg/total precision performance. However, due to the imbalance of the dataset, if there was an opportunity to collect more data and fine tune the models (or find new ones), it would be the preferred recommendation to do so.

# Credit_Risk_Analysis
## Overview
The purpose of this analysis is to use various supervised Machine Learning algorithms to determine which one is most suited to predict if a loan application is considered good or bad.

## Results

### Oversampling
#### Naive Random Oversampling
- The Balanced Accuracy Score is .64 which means that the algorithm predicted the correct results (true negatives and true positives) 64% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/oversampling%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .55 which means that, of those that were positive, the algorithm correctly classified them as positive 55% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/oversampling%20cr.png)

#### SMOTE
- The Balanced Accuracy Score is .66 which means that the algorithm predicted the correct results (true negatives and true positives) 66% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/smote%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .69 which means that, of those that were positive, the algorithm correctly classified them as positive 69% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/smote%20cr.png)

### Undersampling
#### Cluster Centroids
- The Balanced Accuracy Score is .54 which means that the algorithm predicted the correct results (true negatives and true positives) 54% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/undersampling%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .40 which means that, of those that were positive, the algorithm correctly classified them as positive 40% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/undersampling%20cr.png)

### Combined Over and Under Sampling
#### SMOTEENN
- The Balanced Accuracy Score is .64 which means that the algorithm predicted the correct results (true negatives and true positives) 64% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/combined%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .57 which means that, of those that were positive, the algorithm correctly classified them as positive 57% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/combined%20cr.png)

### Ensemble Learning and Random Forests
#### Balanced Random Forest Classifier
- The Balanced Accuracy Score is .78 which means that the algorithm predicted the correct results (true negatives and true positives) 78% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/balanced%20random%20forest%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .87 which means that, of those that were positive, the algorithm correctly classified them as positive 87% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/balanced%20random%20forest%20cr.png)

#### Easy Ensemble Classifier
- The Balanced Accuracy Score is .93 which means that the algorithm predicted the correct results (true negatives and true positives) 93% of the time.
![bs](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/eea%20bs.png)
- The precision is .99 which means that the algorithm is 99% reliable in prediciting positive classifications. Precision = TP/(TP + FP).
- The recall is .94 which means that, of those that were positive, the algorithm correctly classified them as positive 94% of the time. Recall = TP/(TP + FN)
![cr](https://github.com/cailynjmiller/Credit_Risk_Analysis/blob/main/images/eea%20cr.png)

## Summary
Of the algorithm types used, Ensemble Learning and Random Forests appeared to be the most reliable for the loan data source and undersampling appeared to be the least reliable with Oversampling and Combined Over and Under Sampling in the middle. Althought all algorithms varried in balanced accuracy scores and recall, they all had the same precision.<br/>
I would suggest using the Easy Ensemble Classifier algorithm for loan approvals since it had the both the highest balanced accuracy score and recall, making it the most reliable algorithm tested.

# Credit Risk Analysis
## Overview
A series of Machine Learning algorithims is used in a Credit Score dataset to train, evaluate and predict outcomes for lending purposes.

## Process
Data was cleaned and oversampled using **Random Over Sample** and **SMOTE**, undersampled using **Cluster Centroids** algorithm and **SMOTEEN** combinatorial algorithm. Lastly, **Balanced Random Forest Classifier** and **Easy Ensamble Classifier** were used to reduce bias nad predict the credit risk.

## Results
Below there is a summary of all balacned accusracy scores and precision/recall scores of all six Machine Learning models used:

**- Random Oversampling:**

*Accuracy: 63% -
Precision/Recall: 1%/63%*
![Screen Shot 2021-02-28 at 10 54 56 PM](https://user-images.githubusercontent.com/72593264/109453544-fc42ba00-7a17-11eb-900a-499469d16110.png)

![Screen Shot 2021-02-28 at 10 55 29 PM](https://user-images.githubusercontent.com/72593264/109453570-1086b700-7a18-11eb-9379-a060ec895465.png)

**- SMOTE Oversampling**

*Accuracy: 66% -
Precision/Recall: 1%/63%*

![Screen Shot 2021-02-28 at 10 57 35 PM](https://user-images.githubusercontent.com/72593264/109453702-5ba0ca00-7a18-11eb-9865-582e6460edb5.png)

![Screen Shot 2021-02-28 at 10 58 00 PM](https://user-images.githubusercontent.com/72593264/109453736-69564f80-7a18-11eb-9bb8-399ea63a30b6.png)

**- Cluster Centroids Undersampling**

*Accuracy: 53% -
Precision/Recall: 1%/67%*

![Screen Shot 2021-02-28 at 10 59 42 PM](https://user-images.githubusercontent.com/72593264/109453856-a6224680-7a18-11eb-9958-29c0d4365537.png)

![Screen Shot 2021-02-28 at 10 59 58 PM](https://user-images.githubusercontent.com/72593264/109453871-b0444500-7a18-11eb-98c3-5899d86ca4eb.png)

**- SMOTEEN (Over and Under) Sampling**

*Accuracy: 63% -
Precision/Recall: 1%/68%*

![Screen Shot 2021-02-28 at 11 01 38 PM](https://user-images.githubusercontent.com/72593264/109453996-ed103c00-7a18-11eb-8733-5db644164988.png)

![Screen Shot 2021-02-28 at 11 01 58 PM](https://user-images.githubusercontent.com/72593264/109454028-f9949480-7a18-11eb-9c73-b2c37572865f.png)

**- Balanced Random Forest Classifier**

*Accuracy: 72% -
Precision/Recall: 2%/62%*

![Screen Shot 2021-02-28 at 11 03 51 PM](https://user-images.githubusercontent.com/72593264/109454144-3bbdd600-7a19-11eb-9fa7-a808a242f966.png)

![Screen Shot 2021-02-28 at 11 04 17 PM](https://user-images.githubusercontent.com/72593264/109454185-4aa48880-7a19-11eb-9ef0-866a88dc9d21.png)

**- Easy Ensemble Classifier**

*Accuracy: 73% -
Precision/Recall: 2%/69%*

![Screen Shot 2021-02-28 at 11 05 22 PM](https://user-images.githubusercontent.com/72593264/109454267-7293ec00-7a19-11eb-98a7-9b75f67bd43c.png)

![Screen Shot 2021-02-28 at 11 05 42 PM](https://user-images.githubusercontent.com/72593264/109454290-7d4e8100-7a19-11eb-9b42-0c2a5901c215.png)

## Summary

When comparing all the tests, the best results were gathered by the algorithms below:
- Balanced Random Forest Classifier
- Easy Ensemble Classifier

The **Easy Ensemble Classifier** was a  little better then the **Balanced Random Forest Classifier**, however any of the two would give a more accurate prediction then any of the other models analyzed.








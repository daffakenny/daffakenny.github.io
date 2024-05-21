---
title: "HF Patient Survival Classification."
excerpt: "Final Project/Thesis Project for classification of patient survival; achieved 91.11% accuracy, 87.50% recall, and 93.99% AUC." <br/><img src='/images/portfolio1.png' width="500"/>
collection: portfolio
---

Inspired by Davide Chicco & Giuseppe Jurman's [research](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5), my thesis project focused on improving the performance of ML models in predicting patient survival. For this project, I used two datasets. The first one is Chicco & Jurman’s original dataset found on (Kaggle)[https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data]. This dataset is called SOLE DATASET. 

The second dataset was retrieved from Zhang et al. on [PhysioNet](https://physionet.org/content/heart-failure-zigong/1.3/). The second dataset was then combined with Chicco & Jurman's dataset, producing a second dataset called COMBINED DATASET.

Both SOLE and COMBINED dataset were divided into 3 splits, 60/40, 70/30, and 80/20. Each split was used in 5 different way. 1 without resampling, and 4 with resampling (RUS, ROS,SMOTE, ADASYN). Each dataset was then be used with SVM, XGBoost, and Random Forest algorithms, and evaluated with 2 evaluation types: 
* with Cross Validation
* without Cross Validation

With all these different configurations, the best model is achieved with XGBoost. It used 70/30 split of the SOLE DATASET with no resampling, used CrossVal, and achieved  91.11% accuracy, 87.50% recall, and 93.99% AUC.
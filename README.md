# Synthetic-Tabular-Data-Generation-using-CTGAN-and-classify-with-XGboost
This is the repository to generate synthetic tabular data when the tabular data has imbalance in some feature. This was done on the competition in kaggle, [Robi Datathon 2.0: Pre-Assessment](https://www.kaggle.com/competitions/robi-datathon-2-pre-assessment) arranged by Robi. We stood 33 in the private leaderboard. 

It was mainly a classification problem on a tabular data. There were many features including categorical and numerical. We have to first process it to the numerical data. To solve any imbalance in dataset GAN can be used effectively which takes the complex pattern in the consideration. This repository is all about how to generate synthetic data to solve the imbalance in tabular dataset.


# Implementation :
1. Clone this repository
2. Firstly, get the tabular data csv. That csv should contain numerical features only. You should select the under-represented class data so that imbalance can be dispelled.
3. Run the notebook [CTGan_augmentation.ipynb](CTGan_augmentation.ipynb) N.B: You should restart kernel after installing dependencies in the 2nd snippet otherwise error will arise. 
4. Then output csv will be the new synthetic data.


# References 
* https://github.com/jeffheaton/t81_558_deep_learning
* https://arxiv.org/abs/1907.00503

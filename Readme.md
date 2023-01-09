# Tutorial Modeling data Titanic

Tutorial ni akan mengolah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. Instalasi dengan `pip install requirements.txt`
 
 ## Getting Started
 
 - Dataset Splitting
 - Training
 - model Validation
 
 ### Dataset Splitting
 
 split data into training, validation and test sets
 ```code
 X_train, y_train, X_test, y_test = dataset_splitting()
 X_train.shape, y_train.shape
 ```
 
 ## Reference
 
 1. Di scikit-learn documentain
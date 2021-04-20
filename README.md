# Credit Card Default Detection
A data pipeline which tries to maximize the f1-score on credit card default detection.

Banks rely on the fact that the loan they give to their clients is returned to make a profit. If a client doesn't repay the loan they took, the bank would be at a considerable loss; therefore, predicting credit card default and understanding which features are the most contributing factors for someone to default their credit is a vital topic.

F1-Score is used instead of accuracy to train better models because the cases that default are much rarer than people who don't.



## Data 
---
The dataset used is from https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset

## Running Locally

To run the app locally and to modify it, first clone the repo:

```
git clone https://github.com/kshahnazari1998/Credit-Card_Default_Detection.git
```

To get the dependencies of the repo, install conda and go to the root of the project and run

```
conda env create -f environment.yml
```
So that the dependencies for the pipelines get installed.

To see the notebook and be able to rerun the analysis, use the command.
 
 ```
 jupyter lab
 ```

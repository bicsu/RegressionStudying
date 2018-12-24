### Regression 



- Data : https://archive.ics.uci.edu/ml/datasets/Automobile

- Target : 'normalized-losses'
- Ignored to feature 'symboling'
- Using Randomforest regressor model
- Steps :
  1. Loading Files
  2. Data Preprocessing
     - fill the missing values
     - convert numeric values but object types to float type
     - check the distribution of targets
       + taking logs to make it  normal distribution
  3. Detecting Outliers Before Modeling
     - using box plots to get outliers
  4. Normalization of numeric features
  5. One-hot encoding of categorical values
  6. Modeling(fit & predict & evaluation with MSE)
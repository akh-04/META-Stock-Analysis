# META-Stock-Analysis
Using ML techniques to Explore and Create Trading Strategies For META
# INFO7374_Predict_StockPrice

## Objectives:

| **SlNo** | **Status** | **Artifacts** | **Description** |  |
|:---:|---|---|---|---|
| 1 | :hourglass_flowing_sand: | [Google Slides](https://docs.google.com/presentation/d/1JnNtaYrRvWw7uBc9aUbujgMmEZNeJq8VRRPUUj6bko4/edit?usp=sharing) | Presentation slides |  |
| 2 | :white_check_mark: | [1_META EDA_&_Competitor Analysis.ipynb](<./Python Files/META_EDA_1.ipynb>)| Focus on the stock you pick and their competitors<br>Report summary statistics of the training period you select and plot the kernel density |  |
| 3 | :white_check_mark: | [2_Feature_Mart.ipynb](<./Python Files/Feature_Mart_2.ipynb>) | Please use the features/factors you  take and discovered<br>e.g., FRED, Fama-French website, ADS, AR, CAPM, momentum factors, volume, price/return lags, etc. to construct a feature database<br>The target variable Y can be either price or return<br>Frequency could be either daily or monthly |  |
| 4 | :white_check_mark: | [3_Feature_Importance.ipynb](<./Python Files/Feature_Importance_3.ipynb>) | Virtualize the feature importance and feature selection process using regression based approach<br>Ridge regression, LASSO, Elastic Net or LARS **vs** decision tree based approach (random forest, XGBoost) |  |
| 5 | :white_check_mark: | [4_Model_Training.ipynb](<./Python Files/Model_Training_4.ipynb>) | Proposed and train 3-6 models by feeding in the features you prepared in step 2<br>Compare the model performance using RMSE between the fitted Y and actual Y in testing period |  |
| 6 | :white_check_mark: | [5_Benchmark_Study.ipynb](<./Python Files/Kalman_&_GARCH.ipynb>) | Include one benchmark study that uses GARCH or Kalman Filter |  |


## Replication Instructions

:exclamation: Date Range to incldues

* Range = 2022-01-01 ~ 2024-01-31

> :notebook: All notebooks are Colab compatible.



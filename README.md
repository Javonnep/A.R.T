The kaggle competition is <a href="https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques">here</a>

The description of the dataset is [available here](https://wagon-public-datasets.s3.amazonaws.com/Machine%20Learning%20Datasets/ML_Houses_dataset_description.txt). 



In this project I participated in the "House Prices - Advanced Regression Techniques" Kaggle competition. 

- Results: On average, my predictions were within 8.16% of the actual value
- ETL: I used sklearn pipelines to Load my data
- Processing: I used PCA, One-Hot Encoding, Ordinal Encoding, and Imputing(Median/Mode based) to get my results.
- Kaggle: My result was in the top 3rd of all submissions.
- Hyperparameter tuning: Combined `RandomSearchCV` with my pipelines
- Data transformations: Created multiple custom transformer classes by Inheriting from `BaseEstimator`, `TransformerMixin`.

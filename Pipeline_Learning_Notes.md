Recipe Steps using sklearn **compose** and **pipeline** (for all problems):
* `from sklearn.compose import ColumnTransfomer`
* `from sklearn.pipeline import Pipeline`

Sklearn **preprocessing** required imports (based on problem dataset):
* `sklearn.preprocessing import StandardScaler, MinMaxScaler, OneHotEncoder`

Classifer

Sklearn **reprocessing** required imports (based on problem dataset):
* 

* Import `MinMaxScaler`, `StandardScaler` or `OneHotEncoder`

**Supervised Model(s)** Import (based on problem dataset):
* Import


```
# column transformations
from sklearn.compose import ColumnTransformer

# scikit-learn pipleine
from sklearn.pipeline import Pipeline

# preprocessing features
from sklearn.preprocessing import StandardScaler, MixMaxScaler, OneHotEncoder


# train test split, grid search cross validation
from sklearn.model_selection import train_test_split, GridSearchCV
# random forest classifier
from sklearn.ensemble import RandomForestClassifier
# evaluation metric
from sklearn.metrics import accuracy_score
```


**sklearn.preprocessing**

| Name | Description |
| --- | --- |
| preprocessing.MinMaxScaler([feature_range, ...]) | Transform features by scaling each feature to a given range |
| preprocessing.StandardScaler(*[, copy, ...]) | Standardize features by removing the mean and scaling to unit variance |
| preprocessing.OneHotEncoder(*[, categories, ...])	| Encode categorical features as a one-hot numeric array |




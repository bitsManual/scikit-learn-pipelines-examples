### Recipe Steps using sklearn **compose** and **pipeline** (for all problems):
* `from sklearn.compose import ColumnTransfomer`
* `from sklearn.pipeline import Pipeline`
  
---

### Sklearn **preprocessing** required imports (based on problem dataset):
* `from sklearn.preprocessing import StandardScaler, MinMaxScaler, OneHotEncoder`

---

### Classification / Regression based powerful models and evaluation **metrics**:

Models:
* `from sklearn.ensemble import RandomForestClassifier`
* `from sklearn.ensemble import RandomForestRegressor`
* `from xgboost import XGBClassifier`
* `from xgboost import XGBRegressor`

Metrics:
* `from sklearn.metrics import confusion_matrix, accuracy_score, f1_score, precision_recall_curve, precision_score, recall_score, roc_auc_score, roc_curve`
* `from sklearn.metrics import r2_score, root_mean_squared_error, mean_absolute_error`
 
---

### Train-Test Splitter Function

`from sklearn.model_selection import train_test_split`

---

### Hyperparam tuning

`from sklearn.model_selection import GridSearchCV`

---

Example code: 

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


Scikit Learn Pipeline allows to sequentially apply a list of transformers to preprocess the data and, if desired, 
conclude the sequence with a final predictor for predictive modeling.

Main benefits are:
* It allows us to keep all the definitions and components of our model in one place, which makes it easier to reuse the model or change it in the future.
* We can use grid search and cross-validate all the steps of the model together.

| Name | Description |
| --- | --- |
| pipeline.Pipeline(steps, *[, memory, verbose]) | A sequence of data transformers with an optional final predictor |

| Name | Description |
| --- | --- |
| compose.ColumnTransformer(transformers, *[, ...]) | Applies transformers to columns of an array or pandas DataFrame |


<a target="_blank" href="https://colab.research.google.com/github/bitsManual/scikit-learn-pipelines-examples/blob/main/load_iris_RandomForestClassifier.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



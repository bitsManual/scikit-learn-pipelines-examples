Scikit Learn Pipeline allows to sequentially apply a list of transformers to preprocess the data and, if desired, 
conclude the sequence with a final predictor for predictive modeling.

Main benefits are:
* It allows us to keep all the definitions and components of our model in one place, which makes it easier to reuse the model or change it in the future.
* We can use grid search and cross-validate all the steps of the model together.

| Name | Description |
| --- | --- |
| pipeline.FeatureUnion(transformer_list, *[, ...]) | Concatenates results of multiple transformer objects |
| pipeline.Pipeline(steps, *[, memory, verbose]) | A sequence of data transformers with an optional final predictor |
| pipeline.make_pipeline(*steps[, memory, verbose]) | Construct a Pipeline from the given estimators |
| pipeline.make_union(*transformers[, n_jobs, ...]) | Construct a FeatureUnion from the given transformers |



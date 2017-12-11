# is_suicide_prevention

Data and code for significance testing for the Information Sciences article on _Online suicide prevention through optimized text classification_.

## data
Contains predictions on the cross-validation dataset (_n_=10,000) for each system after optimisation. Results are available for the two tasks (relevance and severity) and both optimisation objectives (F1 and F2). For each system, the `_0` column contains the gold standard, and the `_1` column contains the predictions.

## IS2016 Significance.ipynb
IPython notebook with code to do pairwise binomial significance testing, and to generate the significance tables as used in the article.

Run from the terminal using `jupyter notebook`.
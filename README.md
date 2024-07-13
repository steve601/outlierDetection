# Outlier Detection in ML

We all have heard of the idiom ‘odd one out which means something unusual in comparison to the others in a group. Similarly, an Outlier is an observation in a given dataset that lies far from the rest of the observations. That means an outlier treatment is vastly larger or smaller than the remaining values in the set.

## Reasons for outliers in data

1.Errors during data entry or a faulty measuring device (a faulty sensor may result in extreme readings).

2.Natural occurrence (salaries of junior level employees vs C-level employees)

## Problems caused by outliers

1.Outliers in the data may causes problems during model fitting (esp. linear models).

2.Outliers may inflate the error metrics which give higher weights to large errors (example, mean squared error, RMSE).
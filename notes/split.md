# Data Split Solution

I conducted an experiment on splitting the data into training and test samples.

## Previous steps

1. Brute Force
    - [Notebook](../archive/bruteforce.ipynb)
    - [Note](../notes/bruteforce.md)

## Analysis results

### Model quality

- Linear regression of RMSE: 0.732
- RMSE DummyRegressor: 1.154
- Quality improvement: ~37%

> Data partitioning had almost no effect on the quality of the models.

## Possible improvements

1. ~~Divide the data into training and test samples.~~
2. Visualize the data to find correlations and anomalies.
3. Check the zoom effect of the objects.
4. Create new objects based on existing ones.

## Next steps

I will apply feature scaling on the training and test samples.

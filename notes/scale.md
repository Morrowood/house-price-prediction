# Data Split Solution

I conducted an experiment on splitting the data into training and test samples.

## Previous steps

1. Brute Force
    - [Notebook](../archive/bruteforce.ipynb)
    - [Note](../notes/bruteforce.md)
2. Data Split
    - [Notebook](../archive/scale.ipynb)
    - [Note](../notes/scale.md)

## Completed steps

1. Created `StandardScaler`
2. Fitted and transformed train samples
3. Transformed test samples with fitted scaler (on train)

## Analysis results

### Model quality

- Linear regression of RMSE: 0.732
- RMSE DummyRegressor: 1.154
- Quality improvement: ~37%

> Data scaling had almost no effect on the quality of the models.

## Possible improvements

1. ~~Divide the data into training and test samples.~~
2. Visualize the data to find correlations and anomalies.
3. ~~Check the scale effect of the objects.~~
4. Create new features based on existing ones.

## Next steps

I will create new features to try to improve model's score.

# Brute Force Solution

I conducted an experiment to evaluate the quality of models based on data without preparation. The metric used is RMSE.

## Completed steps

1. Connected the necessary libraries.
2. Uploaded the data from the file to pandas.DataFrame.
3. Conducted a primary data analysis:
    - determined the size of the table - 20,640 rows and 9 columns;
    - studied the names and types of columns, as well as the amount of memory used;
    - I got acquainted with the structure and examples of the data.
4. Checked the data for omissions and duplicates.
5. Selected the attributes and the target variable.
6. Created and trained DummyRegressor, then received predictions.
7. Created and trained LinearRegression, then received predictions.
8. Evaluated the quality and compared the results of the models.

## Analysis results

### Dataset

- Number of rows: 20,640
- Number of columns: 9
- Memory capacity: about 1.4 MB
- Missing values: 0
- Duplicate rows: 0

No omissions or duplicates were found. The amount of data is relatively small.

### Target variable
- MedHouseVal

### Model quality

- RMSE LinearRegression: 0,72
- RMSE DummyRegressor: 1,153
- Quality increase: ~37%

> Linear regression showed a smaller error than the basic model. However, both models were evaluated on the entire amount of data.

## Possible improvements

1. Divide the data into training and test samples.
2. Visualize the data to find correlations and anomalies.
3. Check the effect of feature scaling.
4. Create new features based on existing ones.

## Next steps

First, I will divide the data into training and test samples and re-evaluate both models. Then I will conduct an experiment with scaling the features and compare the results on the same test sample.
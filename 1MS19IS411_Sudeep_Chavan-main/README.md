# DL_Assignment
#### dataset: 1.txt

##### Following are the steps:

    - Import pandas and matplotlib.pyplot, seaborn, warnings.
    - Load data using pd.read_csv
    - Calculate mean, median and mode for all columns.
    - Use percentile to find outliers.
    - Visualize outliers
    - Delete verified outliers.
    - Scale the data to fit in a particular range using Maximum Absolute Scaling and MinMax Scaling

Formulas used <br>
Mean = sum(X) / len(X) <br>
Median = mid(sorted(X)) <br>
Min Max Scaler x' = (x - min(X)) / (max(X) - min(X)) <br>
Max Absolute Scaler is x' = x / max(abs(X))

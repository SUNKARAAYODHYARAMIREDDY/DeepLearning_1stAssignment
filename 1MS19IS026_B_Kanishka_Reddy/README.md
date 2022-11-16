Deep Learning Assignment 1
Alloted dataset: 12.txt
Following are the steps:

All necessary packages are imported.
The dataset is read using pd.read_csv
Statistics like mean, median and mode are found.
Found outliers using percentile method.
Only numeric columns are retained.
performed normalization:
Maximum Absolute Scaling
MinMax Scaling
Z-Score
necessary plots are made and anomalies are plotted in black.
Also used distplot to find outliers.
Formulas used
Mean = sum(X) / len(X)
Median = mid(sorted(X))
Min Max Scaler x' = (x - min(X)) / (max(X) - min(X))
Standard Scaler / Z Scaler is x' = (x - mean(X)) / std(X)
Max Absolute Scaler is x' = x / max(abs(X))

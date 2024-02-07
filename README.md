# Python-projects( Mean Normalization and data separation)
Mean Normalization and data separation mini project for python foundations.
- Mean normalization is a machine learning data processing technique to standardize features. It differs from min-max scaling by centering data around 0 rather than in the 0-1 range.

How It Works

- Shifts the data distribution to be centered on 0
- Sets the average (mean) value to 0
- Rescales data to small range (e.g. -3 to 3)
Benefits

Puts all features on a common scale
- Can improve performance of ML algorithms
- Works well for algorithms sensitive to distribution
Usage

- Calculate mean of each feature
- Subtract the mean from each data point
- Optionally, scale to small interval around 0
- Now your data has a mean of 0 and standardized range! Use for preprocessing time series data, images, etc before model training.




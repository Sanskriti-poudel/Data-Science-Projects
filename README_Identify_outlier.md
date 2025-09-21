Outlier Detection

Outliers were identified using the Interquartile Range (IQR) method:

Calculate Q1 (25th percentile) and Q3 (75th percentile)

Compute IQR = Q3 - Q1

Define bounds:

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR

Values outside these bounds are flagged as outliers

Example:
For sample data [10, 12, 12, 13, 12, 11, 10, 250], the value 250 is detected as an outlier.

Standardization and Normalization (Data Preprocessing)

Standardization

Standardization scales numerical data so that it has:
• Mean = 0
• Standard Deviation = 1

It transforms values based on how far they are from the average.

Formula:

```
x' = \frac{x - \mu}{\sigma}
```

When to use:
• When features have different units or scales
• Works well with algorithms like Linear Regression, Logistic Regression, SVM, and PCA

⸻

Normalization

Normalization scales numerical data into a fixed range, usually between 0 and 1.

Formula:

```
x' = \frac{x - x_{min}}{x_{max} - x_{min}}
```

When to use:
• When you want all features in the same range
• Common in Neural Networks and distance-based algorithms like KNN

⸻

Key Difference

Standardization Normalization
Mean = 0, Std = 1 Range = 0 to 1
Not bounded Fixed range
Handles outliers better Sensitive to outliers

⸻

Summary
• Use standardization when data follows a normal distribution
• Use normalization when you need a fixed range for features

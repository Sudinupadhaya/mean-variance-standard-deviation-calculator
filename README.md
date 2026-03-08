# mean-variance-standard-deviation-calculator
freeCodeCamp Data Analysis with Python project
# Mean-Variance-Standard Deviation Calculator

This project is part of the **freeCodeCamp Data Analysis with Python** certification.

It includes a function named `calculate()` in `mean_var_std.py` that uses **NumPy** to calculate:

- Mean
- Variance
- Standard deviation
- Maximum
- Minimum
- Sum

for the:

- Columns
- Rows
- Flattened matrix

## Project Requirements

The function accepts a list of **9 numbers** and converts it into a **3 x 3 NumPy array**.

It returns a dictionary in the following format:

```python
{
  'mean': [axis1, axis2, flattened],
  'variance': [axis1, axis2, flattened],
  'standard deviation': [axis1, axis2, flattened],
  'max': [axis1, axis2, flattened],
  'min': [axis1, axis2, flattened],
  'sum': [axis1, axis2, flattened]
}
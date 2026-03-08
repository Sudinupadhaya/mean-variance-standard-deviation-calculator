
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
```
## Example

## Input

``` calculate([0, 1, 2, 3, 4, 5, 6, 7, 8]) ```

## Output
```
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
  'standard deviation': [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}
```
 ## Files

## Files

- `mean_var_std.py` — main project file
- `main.py` — used for testing the function
- `test_module.py` — unit tests

## How to Run

Run the following command in the terminal:

```bash
python main.py
```


Author

Sudin Upadhaya


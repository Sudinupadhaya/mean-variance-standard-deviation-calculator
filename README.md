# Mean Variance Standard Deviation Calculator

A Python and NumPy project that calculates key statistical measures from a 3x3 matrix. This project is part of the freeCodeCamp Data Analysis with Python certification and demonstrates array manipulation, axis-based calculations, and clean function design.

## Project Objective

The objective of this project is to build a function that accepts a list of 9 numbers, converts it into a 3x3 NumPy array, and calculates summary statistics across rows, columns, and the flattened matrix.

## What the Function Calculates

The `calculate()` function computes:

- Mean
- Variance
- Standard deviation
- Maximum value
- Minimum value
- Sum

Each calculation is performed for:

- Columns
- Rows
- Flattened matrix

## Tech Stack

- Python
- NumPy
- Unit testing

## Project Structure

```text
mean-variance-standard-deviation-calculator/
│
├── mean_var_std.py      # Main calculation function
├── main.py              # Script for local execution
├── test_module.py       # Unit tests
└── README.md            # Project documentation
```

## Function Requirement

The function accepts a list of exactly 9 numbers.

Example input:

```python
calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
```

The list is converted into a 3x3 matrix:

```python
[[0, 1, 2],
 [3, 4, 5],
 [6, 7, 8]]
```

If fewer than 9 numbers are provided, the function should raise a `ValueError`.

## Output Format

The function returns a dictionary:

```python
{
  "mean": [column_result, row_result, flattened_result],
  "variance": [column_result, row_result, flattened_result],
  "standard deviation": [column_result, row_result, flattened_result],
  "max": [column_result, row_result, flattened_result],
  "min": [column_result, row_result, flattened_result],
  "sum": [column_result, row_result, flattened_result]
}
```

## Example Output

```python
{
  "mean": [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  "variance": [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
  "standard deviation": [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],
  "max": [[6, 7, 8], [2, 5, 8], 8],
  "min": [[0, 1, 2], [0, 3, 6], 0],
  "sum": [[9, 12, 15], [3, 12, 21], 36]
}
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Sudinupadhaya/mean-variance-standard-deviation-calculator.git
cd mean-variance-standard-deviation-calculator
```

### 2. Install dependency

```bash
pip install numpy
```

### 3. Run the project

```bash
python main.py
```

### 4. Run tests

```bash
python -m unittest test_module.py
```

## Skills Demonstrated

This project demonstrates:

- NumPy array creation
- Matrix reshaping
- Axis-based statistical calculations
- Dictionary-based result formatting
- Error handling
- Unit testing
- Clean Python function structure

## Why This Project Matters

This project builds a strong foundation for data analysis because statistical summary calculations are commonly used in exploratory data analysis, machine learning preprocessing, and numerical computing.

## Author

**Sudin Upadhaya**

- GitHub: Sudinupadhaya
- Focus areas: Python, Data Analysis, NumPy, Machine Learning, and Software Engineering

## Task 1: Machakos Raw Data Cleaning & Imputation
### Approach
We write a cleaning function that iterates through raw text input, converting valid strings to integers via a `try/except ValueError` block. Invalid entries (`"N/A"`, `""`) are identified, and their values are imputed using the rounded mean of valid readings.
## Task 2: Combine Data into a 5 x 12 NumPy Array
### Approach
We combine all 5 cleaned rows into a single structure and instantiate a 2D NumPy array, explicitly printing its shape (`(5, 12)`) and data type (`int64` or `int32`).

# Reggies_Linear_regression
# Bouncy Ball Data Analysis

## Overview
This project is a Python-based implementation of linear regression using a trial-and-error approach to find the best-fitting line for a given set of data points. The project follows a step-by-step process to calculate the error for different possible lines and selects the best `m` (slope) and `b` (intercept) values that minimize the total error.

## Project Structure
- **Task 1**: Define a function `get_y(m, b, x)` that calculates the y-value for a given x using the equation of a line.
- **Tasks 2 & 3**: Implement `calculate_error(m, b, point)`, which calculates the absolute error between the actual y-value and the predicted y-value.
- **Task 4**: Test the `calculate_error` function with different points.
- **Task 5**: Implement `calculate_all_error(m, b, points)`, which computes the total error for a dataset given a specific `m` and `b`.
- **Task 6**: Test `calculate_all_error` with various test cases.
- **Task 7**: Iterate through sample `m` and `b` values to validate the error calculation function.
- **Tasks 8 & 9**: Generate lists of possible `m` and `b` values to check, using list comprehensions.
- **Task 10**: Initialize `smallest_error`, `best_m`, and `best_b`.
- **Tasks 11 & 12**: Iterate through all possible `m` and `b` values to determine the best-fitting line that minimizes the total error.
- **Task 13**: Use the best-fitting values to predict the bounce height for a ball with a given width.

## Running the Code
To execute this project, simply run the Python script in a compatible environment. The script iterates through a range of values to find the best-fitting line and predicts a value based on the optimized equation.

### Example Output
```plaintext
New best found! m: 0.4, b: 1.6, error: 5.0
Predicted bounce height for a ball with width 6: 4.0
```

## Technologies Used
- Python
- Basic list comprehensions
- Iterative search for best-fit parameters

## Key Learnings
- Implementing and using linear equations
- Calculating error metrics
- Using loops for optimization through brute force

## Future Improvements
- Implement gradient descent for more efficient parameter optimization
- Visualize the dataset and best-fit line using Matplotlib

## Author
This project was completed as part of a Codecademy learning exercise.

## License
This project is open-source and available for educational purposes.


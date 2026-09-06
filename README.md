# PYTHON DATA ANALYSIS (PANDAS): EXPERIMENT#3

This repository contains solutions to three Python programming exercises as part of a Python Programming Experiment.

# EXERCISES:
# A. POSITIONAL AND LABEL-BASED SLICING

Task: Create a reproducible random 5 × 5 integer ndarray named X. where ¯x is the mean of all 25 elements and σ is their population standard deviation as returned by NumPy’s default std() call. Store the normalized array in X normalized.

Required checks: Display X, X normalized, its mean, and its standard deviation. Up to floating-point rounding, the normalized mean must be 0 and the normalized standard deviation must be 1.

# B. MODEL LOOKUP

Task: Using NumPy, create the first 100 positive integers, cube every element, and reshape the result into a 10 × 10 ndarray named C. Thus, C begins with 1^3 and ends with 100^3. Use a Boolean condition on C to obtain every cubed value divisible by 4. Store the selected values in div by 4. Preserve NumPy’s normal row-major selection order.

Required checks: Display the shape of C, the array div by 4, and the number of selected elements. A correct solution has 50 selected elements; the first is 8 and the last is 1,000,000.


# C. MULTI-MODEL SUBSETTING

Task: Create a 6 × 6 ndarray named S containing the squares of the first 36 positive integers in increasing row-major order. Compute the mean of all elements of S and store it in S mean. Then use Boolean filtering to select only the elements strictly greater than S mean. Store these values in above mean.

Required checks: Display S, S mean, above mean, and the number of selected elements. A correct solution has 15 selected elements; the first is 484 and the last is 1296.

# Implementation:
The solutions are implemented in a Jupyter Notebook file (.ipynb) conatining:
1. create and reshape NumPy arrays using appropriate NumPy functions;
2. perform vectorized numerical operations on an ndarray;
3. compute array statistics and use Boolean conditions to select elements

# Learning Outcomes:
Through these exercises, you will:
- Identify complex codes and functions using NumPy in Python Programming

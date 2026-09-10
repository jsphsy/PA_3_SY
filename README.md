# PYTHON DATA ANALYSIS (PANDAS): EXPERIMENT#3

This repository contains a solution to the Python programming exercises for Experiment 3: Python Data Analysis (Pandas) in ECE 2112: Advanced Computer Programming and Algorithms.

# EXERCISES:
# A. POSITIONAL AND LABEL-BASED SLICING

Task: Load the cars.csv dataset into a Pandas DataFrame named cars. Display its shape and complete list of column names. Then, using positional slicing, create a subset containing rows 6 through 10 of the dataset. From this subset, display only the columns Model, mpg, cyl, hp, and gear, in that order.

Required checks:

- The row selection for rows 6–10 uses iloc.

- The requested columns are selected using column labels.

- The original cars DataFrame is not modified.


# B. MODEL LOOKUP

Task: Use Boolean indexing on the Model column to locate specific vehicle records from the dataset.

Required checks: 
- Display the complete row for Toyota Corolla and store the result in toyota.

- Display only Model, mpg, hp, and wt for Pontiac Firebird and store the result in pontiac.

- The models are located using their values rather than hard-coded row numbers.


# C. MULTI-MODEL SUBSETTING

Task: Create a DataFrame named selected_cars containing only the records for:
- Datsun 710
- Lotus Europa
- Ferrari Dino

Retain only the columns Model, mpg, cyl, hp, and gear. Use Boolean filtering based on model values and preserve the source row order.


Required checks: 
- The final DataFrame must have exactly 3 rows and 5 columns.

# Implementation:
The solutions are implemented in a Jupyter Notebook (.ipynb) containing:
1. Importing Pandas as pd and loading the cars.csv dataset;
2. Using positional and label-based indexing with iloc and column labels;
3. Using Boolean indexing and .loc to perform model lookups and multi-model filtering;
4. Displaying the required results and shape checks for Problems A–C.

# LEARNING OUTCOMES:

Through this experiment, you will:

- Load a CSV dataset into a Pandas DataFrame;

- Select rows and columns using positional and label-based indexing;

- Filter records using conditions on a DataFrame column;

- Extract a well-defined subset of data without changing the source data.

FILES:

- PA_3_SY.ipynb — Jupyter Notebook containing the solutions for Problems A–C.

- cars.csv — Dataset used by the notebook (required when executing the notebook).


# **Python for Data Science: Introduction Assignment**

## **Objective:**

To get familiar with Python basics and essential data science libraries like NumPy, Pandas, and Matplotlib. You will perform basic data manipulation, calculations, and create simple visualizations.

---

## **Task 1: Basic Python Operations**

Write a Python script that performs the following:

1. Create a list of 5 random numbers.
2. Print the sum, maximum, and minimum of the numbers in the list.
3. Write a function that takes a number as an input and returns whether the number is odd or even.

**Example:**

```python
numbers = [10, 5, 8, 3, 2]
# Output: Sum: 28, Max: 10, Min: 2
```

---

## **Task 2: Working with NumPy**

Use the NumPy library to perform the following:

1. Create a 2x3 matrix of random integers between 1 and 10.
2. Find the mean and standard deviation of the matrix.
3. Transpose the matrix and print the result.

**Example:**

```python
import numpy as np
matrix = np.random.randint(1, 11, (2, 3))
# Output: Original matrix, mean, std, and transposed matrix
```

---

## **Task 3: Data Analysis with Pandas**

Use the Pandas library to perform the following:

1. Create a DataFrame containing data of your choice (e.g., student names, ages, and grades).
2. Display the first 5 rows of the DataFrame.
3. Calculate the average age or grade from the DataFrame.

**Example:**

```python
import pandas as pd
data = {'Name': ['John', 'Anna', 'Mike', 'Sarah', 'David'],
        'Age': [20, 22, 21, 19, 23],
        'Grade': [88, 92, 95, 85, 91]}
df = pd.DataFrame(data)
# Output: First 5 rows, and average age/grade
```

---

## **Task 4: Data Visualization with Matplotlib**

Use Matplotlib to create a simple bar chart:

1. Plot the grades from Task 3 as a bar chart with student names on the x-axis.
2. Add labels and a title to the chart.

**Example:**

```python
import matplotlib.pyplot as plt
names = ['John', 'Anna', 'Mike', 'Sarah', 'David']
grades = [88, 92, 95, 85, 91]
# Output: A bar chart of student grades
```

---

## **Submission:**

Submit your Python script or Jupyter Notebook file with all tasks completed. Make sure your code is well-commented and easy to follow.

---

### **Bonus Task:**

Use Seaborn to create a more detailed visualization based on the data from Task 3.

author: Parul Pandey
id: course-1
summary: Master the essentials of Pandas and NumPy.
categories: python
status: Published
home_url: https://parulnith.github.io/courses/

# Python for Data Science 101
## Introduction
Welcome! In this module, we cover data manipulation basics - tools every Data Scientist needs. We will focus on the "Holy Trinity" of Python Data Science:
1. **NumPy** for numerical computing.
2. **Pandas** for data manipulation.
3. **Matplotlib** for basic visualization.

## The Foundation: NumPy
Duration: 5:00

NumPy is the backbone of almost all data libraries in Python. It allows for fast operations on arrays.

```python
import numpy as np

# Create a 1D array
arr = np.array([1, 2, 3, 4, 5])

# Perform vector operations
print(arr * 2) 

```

Data Manipulation: Pandas
Duration: 10:00

Pandas introduces the DataFrame, a powerful tool for handling tabular data.

Loading a Dataset
``` Python

import pandas as pd

# Creating a simple dataframe
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['New York', 'London', 'Paris']
}
df = pd.DataFrame(data)
print(df)

```

## Basic Visualization
Duration: 8:00
Before using advanced libraries, it's important to understand matplotlib.

```python

import matplotlib.pyplot as plt

plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
plt.title("Simple Growth Chart")
plt.show()

```

## Interactive Notebook
Duration: 5:00

You can interact with the live code below. Try changing the sliders or inputs to see the results update in real-time.

<iframe 
    src="https://molab.marimo.io/notebooks/nb_TWVGCgZZK4L8zj5ziUBNVL?embed=true" 
    width="100%" 
    height="600px" 
    frameborder="0" 
    style="border: 1px solid #e2e8f0; border-radius: 8px;">
</iframe>

> Note: If the notebook doesn't load, ensure you have an active internet connection.

## Summary and Quiz
Duration: 3:00

You've successfully:

Learned how to use NumPy arrays.

Created your first Pandas DataFrame.

Visualized basic data points.

Next Step: Head over to Course 2: Visual Storytelling to learn how to make these charts look professional.

# What is Numpy?

## Introduction

In this lesson, we are going to introduce the Python library, *NumPy*. Why? Besides being ubiquitous to data science, NumPy also provides us with blistering fast and efficient list-like data types called N-Dimensional Arrays or **ndarray**s or more simply arrays. This list-like data type is effectively a lighter weight version of a Python **list**, as it uses less of your computer's memory, which makes it more efficient when you are dealing with large datasets. Don't worry if that seems a little vague. We will take a closer look at NumPy and how its arrays work in this lesson.

## Objectives
* How to get started with NumPy
* What is the difference between a NumPy Array and a Python List
* Understand how and when to use a NumPy Array
* Performance Benefits of a NumPy Array

## Getting Started With NumPy

Just like with any other library, we need to first install the library with a package manager like `pip`. We have already installed this library in the background, so, no need to worry about this step. Next, we need to import the dependency into our code. 

The conventional method to import NumPy is by aliasing it as `np`. Let's check out an example below.


```python
import numpy as np
print("Woo! we imported NumPy. Here it is:", np)
```

That was easy! Now we can use any functions from the NumPy library by simply typing `np.FUNCTION_NAME`. For example, if we wanted to create a NumPy array containing the values 1, 2, 3, and 4, we would write `np.arry([1,2,3,4])`. Let's try it out below:


```python
num_py_arr = np.array([1,2,3,4])
print("Here is a NumPy Array:", num_py_arr)
print("You know it is a NumPy Array because:", type(num_py_arr))
```

## Numpy Arrays and Python Lists: What's the Difference Anyway?

## How and When to Use a NumPy Array

## Performance Benefits of a NumPy Array

## Summary

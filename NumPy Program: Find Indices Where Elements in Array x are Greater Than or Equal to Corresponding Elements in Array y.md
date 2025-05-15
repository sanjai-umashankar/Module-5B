# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

```
import numpy as np

# Define arrays
x = np.array([5, 8, 2, 9, 6])
y = np.array([3, 8, 4, 7, 6])

# Find indices where x >= y
indices = np.where(x >= y)

# Display result
print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices[0])

```

## Output
![image](https://github.com/user-attachments/assets/d6bbd098-723c-4753-a592-d9ca11c380fb)
## Result
Thus the program has been successfully executed

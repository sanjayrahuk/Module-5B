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
x=eval(input())
y=eval(input())
l1=np.array(x)
l2=np.array(y)

print(np.where(l1>l2))
print(np.where(l1==l2))
```

## Output
![438782359-5bb4e29b-f3ad-45f9-bea7-3c754408a985](https://github.com/user-attachments/assets/2340559b-e44b-4c33-841a-95f03d944de0)

## Result
Thus the python program for element wise comparison between two numpy array has been implemented and executed successfully

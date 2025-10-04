# Numpy_
The basis of NUMPY

It is a Python library that provides a multidimensional array object and various derived object such as matrices.
 
 •Handle data easily 
 
 •Faster calculation 
 
 •Less memory
 
 •Faster Speed

- Used for calculation of millions of numbers easily

- Used in Data science, Machine Learning (AI), Stock Market and Finance, Medical Research and Image Processing.

# Creating arrays from python list
import numpy as np

numpy_array = np.array([1,2,3,4,5])

print(numpy_array)

# Creating identity matrices
import numpy as np

Identity_matrix = np.eye(3)

print(identity _matrix)

# Creating one dimensional array
import numpy as np

arr_1d = np.array([10,20,30,40,50])

print(arr_1d)

# Creating two dimensional array
import numpy as np
arr_2d = np.array([[1,2,3],
                 [4,5,6],
                 [7,8,9]])

print(arr_2d)

# Creating multi dimensional array
import numpy as np

matrix = np.array([[2,4,6],
                 [8,10,12]])

print(matrix)

# Shape and size of array
import numpy as np

arr_2d = no.array([[1,2,3],
                 [4,5,6]])

print(arr_2d.shape)

print(arr_2d.size)

# Finding dimensions of array
import numpy as np 

arr_1d = np.array([1,2,3])

arr_2d = np.array([[1,2,3],[4,5,6])

print(arr_1d.ndim)

print(arr_2d.ndim)

# Data type
import numpy as np

arr = np.array([10,20,30.5,40])

print(arr.dtype)

# Operation on array
import numpy as np

arr = np.array([10,20,30])

print(arr+5)

print (arr*3)

print(arr**2)


import numpy as np

arr = np.array([10,20,30,40,50])

print(np.sum(arr))

print(np.mean(arr))

print(np.max(arr))

print(np.min(arr))

print(np.std(arr))

# Indexing 
import numpy as np 

arr = np.array([10,20,30,40,50])

print(arr[0])

print(arr[2])

# Slicing
import numpy as np

arr = np.array([10,20,30,40,50,60])

print(arr[1:5])

print(arr[:4])

print(arr[::-1])




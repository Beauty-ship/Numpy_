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

Output 

[1 2 3 4 5]

# Creating identity matrices
import numpy as np

Identity_matrix = np.eye(3)

print(identity _matrix)

Output 

[[1 0 0]
 
 [0 1 0]
 
 [1 0 0]]
 
# Creating one dimensional array
import numpy as np

arr_1d = np.array([10,20,30,40,50])

print(arr_1d)

Output 

[10 20 30 40 50]

# Creating two dimensional array
import numpy as np
arr_2d = np.array([[1,2,3],
                 [4,5,6],
                 [7,8,9]])

print(arr_2d)

Output 

[[1 2 3]
 
 [4 5 6]
 
 [7 8 9]]
 
# Creating multi dimensional array
import numpy as np

matrix = np.array([[2,4,6],
                 [8,10,12]])

print(matrix)

Output 

[[2 4 6]
 
 [8 10 12]]
 
# Shape and size of array
import numpy as np

arr_2d = no.array([[1,2,3],
                 [4,5,6]])

print(arr_2d.shape)

print(arr_2d.size)

Output 

(2,3)

6

# Finding dimensions of array
import numpy as np 

arr_1d = np.array([1,2,3])

arr_2d = np.array([[1,2,3],[4,5,6])

print(arr_1d.ndim)

print(arr_2d.ndim)

Output

1

2

# Data type
import numpy as np

arr = np.array([10,20,30.5,40])

print(arr.dtype)

Output 

float

# Operation on array
import numpy as np

arr = np.array([10,20,30])

print(arr+5)

print (arr*3)

print(arr**2)

Output

[15 25 35]

[30 60 90]

[100 400 900]

import numpy as np

arr = np.array([10,20,30,40,50])

print(np.sum(arr))

print(np.mean(arr))

print(np.max(arr))

print(np.min(arr))

print(np.std(arr))

Output 

150

30.0

50

10

200.0

# Indexing 
import numpy as np 

arr = np.array([10,20,30,40,50])

print(arr[0])

print(arr[2])

Output 

10

30

# Slicing
import numpy as np

arr = np.array([10,20,30,40,50,60])

print(arr[1:5])

print(arr[:4])

print(arr[::-1])

Output 

[20 30 40 50]

[10 20 30 40]

[60 50 40 30 20 10]


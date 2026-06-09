**Introduction to NumPy**
- The **NumPy** package provides tools for mathematical computations in Python
- NumPy provides a multidimensional **array** object, conceptually similar to a list, consisting of an ordered set of elements of the same type

**NumPy Arrays**
- The NumPy array data type is called **ndarray**, where "nd" stands for N-dimensional and N can be any number of dimensions
- The **shape** of an array is a tuple of the lengths of each of the array's dimensions. The **size** of an array is the total number of elements in an array

**Array Axes**
- A NumPy array **axis** is a direction along each array dimension

**Creating and Modifying Arrays**

| Function/Method                                                | Description                                                                                                                                                                                                              | Example                                                                                                                                                                                 |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| array(object)                                                  | Returns an ndarray based on a given object, like a list.                                                                                                                                                                 | # Creates a 1D (4,) array based off of a list<br>array1D = np.array([1, 2, 3, 4])<br><br># Creates a 2D (2, 2) array based off of 2 lists<br>array2D = np.array([ [1, 2], [3, 4] ])     |
| zeros(arrShape)<br>ones(arrayShape)<br>full(arrayShape, value) | Returns an ndarray of a specified shape filled with zeros, ones, or a specified value.                                                                                                                                   | # Creates a 2D (2, 2) array filled with 6s<br># [ [6, 6], [6, 6] ]<br>array_6fill = np.full((2, 2), 6)                                                                                  |
| array[row_index, col_index]                                    | Returns the element located at indices [row_index, col_index].                                                                                                                                                           | array2D = np.array([ [1, 2], [3, 4] ])<br><br># Returns 3: Element located at second row (index 1), first column (index 0)<br>elem_1_0 = array2D[1, 0]                                  |
| delete(ndarray, obj, axis)                                     | Returns a new ndarray with a row or column deleted from the given ndarray. Deletes the row or column indicated by obj. If axis = 0, delete row. If axis = 1, delete column.                                              | array2D = np.array([ [1, 2], [3, 4] ])<br><br># Returns a new 1D (1x2) array with the second row (obj 1, axis 0) ([3,4]) removed<br># [1, 2]<br>new_a1D = np.delete(array2D, 1, axis=0) |
| ndarray.sort(axis)                                             | Sorts an ndarray in place in ascending order along an axis. If axis=None, the array is flattened into a 1D array, and then sorted. If no argument is passed, sorting occurs along the last axis (axis 1 for a 2D array). | my_array = np.array([2, 4, 1, 3])<br><br># Sorts a 1D array in place<br># [1, 2, 3, 4]<br>my_array.sort()                                                                               |
| ndarray.ravel()                                                | Returns a flattened (1D) version of the given ndarray.                                                                                                                                                                   | array_7 = np.array([ [7, 7], [7, 7] ])<br><br># Returns a new flattened 1D (4,) version of a 2D (2, 2) array<br># [7, 7, 7, 7]<br>array_7flat = array_7.ravel()                         |
| ndarray.reshape(new_shape)                                     | Returns a new ndarray containing the elements of the given ndarray with a new shape.                                                                                                                                     | array1D = np.array([1, 2, 3, 4])<br><br># Returns a new reshaped 2D (2, 2) version of a 1D (4,) array<br># [ [1, 2], [3, 4] ]<br>a_reshaped = array1D.reshape((2,2))                    |
| ndarray.transpose()                                            | Returns the transpose of an ndarray.                                                                                                                                                                                     | # Returns a new transposed version of a_reshaped<br># [[1, 3], [2, 4]]<br>array1_transposed = a_reshaped.transpose()                                                                    |

**Mathematical Operations**

| Expression                | Description                                                                                                          |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| array1 + array2           | Element-wise addition                                                                                                |
| array1 - array2           | Element-wise subtraction                                                                                             |
| array1 * array2           | Element-wise multiplication                                                                                          |
| array1 / array2           | Element-wise division                                                                                                |
| np.sqrt(array1)           | Square root of array elements                                                                                        |
| np.log(array1)            | Logarithm of array elements                                                                                          |
| np.sin(array1)            | Sine of array elements                                                                                               |
| np.max(array1)            | Maximum of array elements                                                                                            |
| np.median(array1)         | Median of array elements                                                                                             |
| np.std(array1)            | Standard deviation of array elements                                                                                 |
| np.var(array1)            | Variance of array elements                                                                                           |
| np.dot(array1, array2)    | Dot product of array1 and array2                                                                                     |
| np.matmul(array1, array2) | Also the dot product of array1 and array2 but with subtle difference from dot() when either array has dimension >= 3 |
| np.cross(array1, array2)  | Cross product of array1 and array2                                                                                   |

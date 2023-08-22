1. **Create an Array**:
   Create a 1D array containing the numbers from 1 to 10.

```python
import numpy as np

numbers = np.arange(1, 11)
print(numbers)
```

2. **Reshape Array**:
   Reshape the previous 1D array into a 2D array with 2 rows and 5 columns.

```python
reshaped_numbers = numbers.reshape(2, 5)
print(reshaped_numbers)
```

3. **Element-wise Operations**:
   Create two arrays with the same shape and perform element-wise addition and multiplication.

```python
array1 = np.array([1, 2, 3])
array2 = np.array([4, 5, 6])

sum_result = array1 + array2
product_result = array1 * array2

print("Sum:", sum_result)
print("Product:", product_result)
```

4. **Calculate Statistics**:
   Create a random 1D array of 10 numbers and calculate its mean, median, and standard deviation.

```python
random_numbers = np.random.rand(10)
mean = np.mean(random_numbers)
median = np.median(random_numbers)
std_dev = np.std(random_numbers)

print("Random Numbers:", random_numbers)
print("Mean:", mean)
print("Median:", median)
print("Standard Deviation:", std_dev)
```

5. **Matrix Operations**:
   Create two matrices and perform matrix multiplication between them.

```python
matrix1 = np.array([[1, 2], [3, 4]])
matrix2 = np.array([[5, 6], [7, 8]])

matrix_product = np.dot(matrix1, matrix2)

print("Matrix 1:\n", matrix1)
print("Matrix 2:\n", matrix2)
print("Matrix Product:\n", matrix_product)
```

6. **Indexing and Slicing**:
   Create a 1D array and print the second and third elements.

```python
array = np.array([11, 22, 33, 44, 55])
print("Second Element:", array[1])
print("Third Element:", array[2])
```

These exercises cover a range of basic operations you can perform with NumPy. As you work through these examples, you'll become more comfortable with the syntax and capabilities of the library. Feel free to modify and expand upon these exercises to practice further!
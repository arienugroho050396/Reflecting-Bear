![This is an image](https://github.com/arienugroho050396/Reflecting-Bear/blob/main/header.png)
> I will share an example of an assignment that I did when I was in the Machine Learning with TensorFlow bootcamp organized by **Google x Digital Talent Scholarship 2022**. The topic discussed was Mathematical Linear Agreba.
 
## Background
Panda Bear is confused. He is trying to work out how things should look when reflected in a mirror, but is getting the wrong results.
As is the way with bears, his coordinate system is not orthonormal: so what he thinks is the direction perpendicular to the mirror isn't actually the direction the mirror reflects in.
Help Bear write a code that will do his matrix calculations properly!  

## Instructions
In this assignment you will write a Python function that will produce a transformation matrix for reflecting vectors in an arbitrarily angled mirror.

Building on the last assingment, where you wrote a code to construct an orthonormal basis that spans a set of input vectors, here you will take a matrix which takes simple form in that basis, and transform it into our starting basis.
 
You will write a function that will construct this matrix.
This assessment is not conceptually complicated, but will build and test your ability to express mathematical ideas in code.
As such, your final code submission will be relatively short, but you will receive less structure on how to write it.

### Matrices in Python
For this exercise, we shall make use of the @ operator again.
Recall from the last exercise, we used this operator to take the dot product of vectors.
In general the operator will combine vectors and/or matrices in the expected linear algebra way,
i.e. it will be either the vector dot product, matrix multiplication, or matrix operation on a vector, depending on it's input.

One would use the code,
```python
a = s @ t
s = A @ t
M = A @ B
```
(This is in contrast to the \\(*\\) operator, which performs element-wise multiplication, or multiplication by a scalar.)

You may need to use some of the following functions:
```python
inv(A)
transpose(A)
gsBasis(A)
```
These, respectively, take the inverse of a matrix, give the transpose of a matrix, and produce a matrix of orthonormal column vectors given a general matrix of column vectors - i.e. perform the Gram-Schmidt process.
This exercise will require you to combine some of these functions.

## Output
![This is an image](https://github.com/arienugroho050396/Reflecting-Bear/blob/main/bear.png)

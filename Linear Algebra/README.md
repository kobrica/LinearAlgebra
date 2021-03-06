# Mathematics for Machine Learning-Linear Algebra (Imperial College London)
Programming Assignment 1:  (code inside specialmatrices.py)
      Identifying special matrices
Instructions
In this assignment, you shall write a function that will test if a 4×4 matrix is singular, i.e. to determine if an inverse exists, before calculating it.

You shall use the method of converting a matrix to echelon form, and testing if this fails by leaving zeros that can’t be removed on the leading diagonal.

Don't worry if you've not coded before, a framework for the function has already been written. Look through the code, and you'll be instructed where to make changes. We'll do the first two rows, and you can use this as a guide to do the last two.

Matrices in Python
In the numpy package in Python, matrices are indexed using zero for the top-most column and left-most row. I.e., the matrix structure looks like this:

A[0, 0]  A[0, 1]  A[0, 2]  A[0, 3]
A[1, 0]  A[1, 1]  A[1, 2]  A[1, 3]
A[2, 0]  A[2, 1]  A[2, 2]  A[2, 3]
A[3, 0]  A[3, 1]  A[3, 2]  A[3, 3]
You can access the value of each element individually using,

A[n, m]
which will give the n'th row and m'th column (starting with zero). You can also access a whole row at a time using,

A[n]
Which you will see will be useful when calculating linear combinations of rows.

A final note - Python is sensitive to indentation. All the code you should complete will be at the same level of indentation as the instruction comment.

Programming Assignment 2: 
Gram-Schmidt process
Instructions
In this assignment you will write a function to perform the Gram-Schmidt procedure, which takes a list of vectors and forms an orthonormal basis from this set. As a corollary, the procedure allows us to determine the dimension of the space spanned by the basis vectors, which is equal to or less than the space which the vectors sit.

You'll start by completing a function for 4 basis vectors, before generalising to when an arbitrary number of vectors are given.

Programming Assignment 3 :
Panda Bear is confused. He is trying to work out how things should look when reflected in a mirror, but is getting the wrong results. As is the way with bears, his coordinate system is not orthonormal: so what he thinks is the direction perpendicular to the mirror isn't actually the direction the mirror reflects in. Help Bear write a code that will do his matrix calculations properly!

Programming Assignment 4 : Page Rank Algorithm Implementation

Vector addition and multiplication by scalar values will play an important role in Linear Algebra. 

In Linear Algebra, it is almost always the case that the vector will have it's tail at the origin. 

Another way to view this is as a matrix shown below: 
$$
\begin{bmatrix}
-2 \\
3
\end{bmatrix}
$$
It is useful to think of this as a set of directions. From the origin, go -2 in the $x$ direction and 3 in the $y$ direction. 

Matrices can be extended in any direction. Here is an example of a 3D matrix: 
$$
\begin{bmatrix}
2 \\
1 \\
3
\end{bmatrix}
$$
![[Pasted image 20250107112832.png]]

# [[Vector Addition]]
To add vectors, you take one vector and put it's tail on the other's head. Draw a new vector from the origin to where the moved vector's head now points, and this new vector represents the sum of the two original vectors. 

#### Visual Representation: 
![[Pasted image 20250107113053.png]]
![[Pasted image 20250107113122.png]]

#### Numerical Representation: 

$$
\begin{bmatrix}
1 \\
2
\end{bmatrix}
+ \begin{bmatrix}
3 \\
-1
\end{bmatrix}
= \begin{bmatrix}
4 \\
1
\end{bmatrix}
$$
And we can come to the following equation:
$$
\begin{bmatrix}
x_{1}  \\
y_{1}
\end{bmatrix}
+
\begin{bmatrix}
x_{2}  \\
y_{2}
\end{bmatrix}
= 
\begin{bmatrix}
x_{1} + x_{2} \\
y_{1} + y_{2}
\end{bmatrix}
$$
# [[Vector Multiplication by Scalar Quantities]]
#### Numerical Representation:
Multiplying a vector by a scalar quantity means that you are either stretching or compressing the vector by that scalar quantity. 
$$
2 \cdot \begin{bmatrix}
3 \\
1
\end{bmatrix}
=
\begin{bmatrix}
6 \\
2 \\
\end{bmatrix}
$$
$$
\frac{1}{3} \cdot \begin{bmatrix}
3 \\
1
\end{bmatrix}
=
\begin{bmatrix}
1 \\
\frac{1}{3}
\end{bmatrix}
$$
You can also perform vector multiplication by negative scalar quantities. For this, you simply go in the opposite direction of the original vector. 
$$
-2 \cdot \begin{bmatrix}
3 \\
1
\end{bmatrix}
= 
\begin{bmatrix}
 -6 \\
-2
\end{bmatrix}
$$

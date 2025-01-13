### Linear Equations:
$$
a_{11}x_{1} +a_{12}x_{2} + \dots + a_{1n}x_{n} = b
$$
$$
a_{21}x_{1} + a_{22}x_{2}+ \dots + a_{2n}x_{n} = b_{2}
$$
$$
\dots
$$
$$
a_{m_{1}}x_{1}+ a_{m_{2}}x_{2} + \dots + a_{mn}x_{n} = b_{m}
$$
	- This is a linear system
	- Just because there is an $a$ somewhere doesn't mean that they aren't zeroes. 
#### Linear systems contain no solutions, one solution, or infinitely many solutions.

### Example: 

$$
x_{1}-2x_{2}+ -x_{3}
$$
$$
-x_{1}+3x_{2}+3x_{3}
$$
- Does a solution exist?
	- Yes
		- Is the solution unique?
			- Yes
				- There is one solution
			- No
				- There are infinitely many solutions
	- No
		- There are no solutions

#### Establish existence and uniqueness
- Matrix Representation: Coefficient Matrix
$$
\begin{bmatrix}
1 & -2 \\
-1 & 3  
\end{bmatrix}
$$

- Matrix Representation: Augmented Matrix
$$
\begin{bmatrix}
 1 & -2 & -1 \\
-1 & 3 & 3 \\
\end{bmatrix}
$$
- Rows represent different equations, columns represent the related variables within the system of equations

### Solution Set:
- Two matrices are row equivalent if they have the same solution and one is obtained from the other using row operations.

### Legal Row Operations:
- Scale the equations(not by 0):
$$
R_{1} = kR_{1}, k\neq 0
$$
- Replace:
$$
R_{1} = R_{1} + kR_{2}
$$
- Swap/Reordering:
$$
R_{1} \iff R_{2}
$$

### Example: Augmented Matrix
$$
\begin{bmatrix}
1 & 0 & 0 & 1 \\
0 & 1 & 0 & 2 \\
0 & 0 & 1 & 3
\end{bmatrix}
$$
- Solution exists and is unique

$$
\begin{bmatrix}
1 & 0 & 0 & 1 \\
0 & 0 & 1 & 2 \\
0 & 0 & 0 & 0
\end{bmatrix}
$$
- Solution exists, but it is not unique. 
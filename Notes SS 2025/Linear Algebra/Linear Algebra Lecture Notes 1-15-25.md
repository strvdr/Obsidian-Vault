
For what values of H and K does this system have exactly one solution, infinite solutions, and no solutions
$$
x_{1} + hx_{2} = 2
$$
$$
4x_{1} + 8x_{2} = k
$$
Turn it into a matrix: 
$$
\begin{bmatrix}
1&h&2 \\
4 & 8 & k
\end{bmatrix}
$$
Row reduce using:
$$
R_{2} \leftarrow R_{2}+(-4)R_{1}
$$
To achieve this matrix:
$$
\begin{bmatrix}
1 & h & 2 \\
0 & 8-4h & k-8
\end{bmatrix}
$$
To find exactly one solution, you must eliminate free variables. 
$$
h\neq 2, k \text{ is any real number}
$$
To find more than one solution, row reduce such that the free variables are located in the pivot column
$$
h=2,k=8
$$
### Definition:
If $\vec{v_{1}},\dots,\vec{v_{p}}$ are in $\mathbb{R}^n$, then the set of all linear combinations of $\vec{v_{1}},\dots,\vec{v_{p}}$ is called: 
$$
span{\{\vec{v_{1}},\dots,\vec{v_{p}}\}}
$$
Also: This set is spanned by $\{\vec{v_{1}},\dots ,\vec{v_{p}}\}$. 
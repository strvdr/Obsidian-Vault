### Initial Value Problems
$$
n =1, \frac{dy}{dx}=2y
$$
Family: 
$$
y=Ce^{2x}
$$
$$
y'=2Ce^{2x}
$$
### Go from a family of solutions to a particular solution
$$
IC=y(0)=10
$$
$$
y(0)=Ce^{2(0)}
$$
$$
=C*1
$$
$$
\implies C = 10
$$

### IVP Order n
ODE:
$$
\frac{d^n(y)}{dx^n}=f(x,y,y',y'',\dots,y^{(n-1)})
$$
Need n initial conditions:
$$
y(x_{0})=y_{0}
$$
$$
y'(x_{0)}) = y_{1}
$$
$$
y''(x_{0)}) = y_{2}
$$
$$
\dots
$$
$$
y^{(n-1)}(x_{0}) = y_{(n-1)}
$$

### Practice

$$
y''=6y+5y'
$$

Family of Solutions:
$$
C_{1}e^{2x}+C_{2}e^{3x}
$$

Solve the IVP w/ IC's:
$$
y(0) = 1
$$
$$
y'(0)=1
$$
$$
C_{1}+C_{2}=1
$$
$$
y={2}e^{2x}+e^{3x}
$$
- Recall that a solution has an interval of definition, I. 
	- Also called domain of solution, interval of existence...

		- For this particular problem, any value of x can be substituted, therefore 
$$
I=(-\infty,\infty)
$$
#### Example: Show that $1/x$ is a solution to IVP:
$$
xy' + y = 0, y(1)=1
$$
$$
y'=-\frac{1}{x^2}
$$
LHS:
$$
x\left( -\frac{1}{x^2} \right) + \frac{1}{x}=0
$$
IC:
$$
y(1)=\frac{1}{1}=1
$$
What is the interval of definition?
1. Find domain of **function**
$$
y=\frac{1}{x}
$$
$$
D = \{ x:x\neq_{0} \}
$$
$$
= (-\infty,0) \bigcup(0,\infty)
$$
2. Now, Find I:
	- I has to be an interval
	- I must contain $x_{0}=1$ from IC 
$$
I=(0,\infty) \text{ which contains }x_{0}=1
$$
### Other Intervals that would work:
$$
I=(0,6)
$$
$$
I=\left[ \frac{1}{2}, \infty \right]
$$
By convention, we choose the largest possible interval. 


### Practice:
$$
\text{Show that }\sqrt{ x } \text{ is a solution to } y'=\frac{1}{2y}, y(9)=3
$$
$$
y' = \frac{1}{2\sqrt{ x }}
$$
$$
y(9) = \sqrt{ 9 }=3
$$
Find I:
$$
y=\sqrt{ x } \text{ has domain }[0, \infty)
$$
$$
I=(0,\infty)
$$
### Theorem: Existence of a Unique Solution

Given IVP $y'=f(x,y)$ <-- ODE order 1
$$
y(x_{0})=y_{0}
$$
$$
\text{Let }R = \{  {(x,y): a\leq x\leq b, c\leq y\leq d}\} \text{ contains } (x_{0},y_{0})
$$
$$
\text{If f and} \frac{\partial f}{\partial y} \text{ are continuous on R, then there exists some interval }I_{0} 
$$
$$
\text{ about } x_{0} \text{ on which there is a unique solution}
$$

### Important Points: 
- If an IVP does not meet the conditions of the theorem above, then the theorem does not apply.
	- When the theorem does not apply,
		- IVP might have a unique solution
		- IVP might have more than one solution
		- IVP might not have any solutions(no solutions)
	
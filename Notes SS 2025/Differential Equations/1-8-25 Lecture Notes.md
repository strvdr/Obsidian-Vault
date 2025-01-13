Worksheet 01 Due 1/15

### 1.1 Definitions and Terminology

#### Classifications of Differential Equations
- Types: ODE, PDE
- Order: Highest order derivative in the DE
$$
y' + 5y = e^x
$$
		- Order n=1, ODE
$$
\frac{\partial^2(u)}{\partial(x)^2}
- \frac{\partial^2(u)}{\partial(x)^2} = \frac{2\partial(u)}{\partial(x)}
$$
		- Order n=2, PDE

#### General Form for ODEs
$$
F(x, y, y', y'', \dots, y^{(n-1)}) = g(x) = \text{(often)} 0
$$
#### Linearity
- An order n ODE is said to be linear if it is of the form
$$
a_{n}(x)y^n + a_{n-1}(x)y^{(n-1)} + \dots + a_{1}(x)y' + a_{0}(x)y = g(x)
$$
	- Functions of an independent variable $a_{n}(x)$ and derivatives of dependent variable $y^n$ 

- Otherwise, the ODE is nonlinear
$$
y'' + 3y' + y = 13x
$$
		- However, this example is an order n=2 linear ODE
$$
y''+\sqrt{ y } = e^x
$$
		- Order 2 ODE, but the square root makes this DE nonlinear.
$$
y' \cdot y + x = 0
$$
		- Order 1 ODE, also nonlinear due to the product computed with y

### Examples: ODE, Find Order and Linearity
$$
xy''' - (y')^4 + y = 0
$$
$$
2y'' + x = -y\cos(x)+e^x
$$
$$
5y'' + 2y' + 3y = x^2 + e^x
$$
$$
\frac{dP}{dt} = \frac{1}{2}P\left( 1-\frac{P}{200} \right)
$$
#### Solutions:
1. Order 3, nonlinear
1. Order 2, linear
2. Order 2, linear
3. Order 1, nonlinear

### Definitions:
ODE Solution: A solution to an order n ODE is a $/phi (x)$ that 
	- is defined on an interval I
	- has atleast n derivatives that are continuous on I
	- satisfies the ODE on I
$$
I = (-\infty,\infty)
$$
$$
I = [a,b]
$$
$$
I = (-1, \infty)
$$
*** A solution always has an associated I

Interval: The I in the previous definition has several names
	- Interval of Existence, Definition, Validity
	- Domain of the Solution

### Solution Types:
Explicit Solutions:
$$
y = \phi(x)
$$
	Example: 
		Verify that $y=\frac{1}{4-x^2}$ satisfies the DE $y' = 2xy^2$
	Solution:
		Find derivatives of y.
		$y' = 2x(4-x^2)^{-2}$
		$\frac{2x}{(4-x^2)^2} \equiv 2xy^2$

Implicit Solutions:
	Relation $G(x,y)=0$ is true on I for some $y=\phi(x)$
	Example:
		$$
G(x,y) = x^2 + y^2 - 25 = 0
$$
is an implicit solution to the DE $\frac{dy}{dx} = -\frac{x}{y}$ 

	Verify: 

$$
\frac{d}{dx}(x^2 + y^2 - 25) = \frac{d}{dx}(0)
$$
$$
2x + 2yy' + 0 = 0
$$
	Solve for y'

$$
y' = -\frac{2x}{2y} = -\frac{x}{y}
$$
Family of Solutions:
	A family of solutions is a solution w/ arbitrary constants
	e.g. $y=2x^2+C$

A Particular Solution: 
	A particular solution has no arbitrary constants
	e.g. $y=2x^2+7$
	We can often go from a family to a particular using initial conditions

### 1.2 Initial Value Problems
The order n ODE:
$$
\frac{d^n(y)}{dx^n} = f(x, y, y', \dots, y^{n-1})
$$
has a family of solutions. 

Ex. 1
$$
n = 1, \frac{dy}{dx} = 2y
$$
has a solution of $y=Ce^{2x}$
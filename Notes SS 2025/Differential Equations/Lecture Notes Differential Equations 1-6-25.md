## About
Dr. Tommy Guess ~ tommy.guess@mines.edu 
Section J ~ MWF @ 1:00pm
Office Hours: Monday 9:30-10:30 am, Wednesday 4-6pm
## Textbook
Differential Equations with Boundary Value Problems, 9th ed., Zill
	- Very readable
	- Course will follow the textbook closely
## Grades:
45% In-Semester Exams (2 weighted equally)
30% Comprehensive Final Exam
10% WebAssign Homework
15% Worksheets
## Exam Conflicts
I have an exam conflict for both existing scheduled exams, as they are the same day as the Linear Algebra exams. Email either Dr. Guess or Dr. Bridgman about this.
## Why Differential Equations?
#### Physical Quantities are Related 
	- Classic example: F = m(dv/dt) (F=ma)
	- Traffic Flow
	- Four Bug Problem
	- Fastest Path Under Gravity (brachistochrone)
	- Fluids
	- Electrical Circuits
	- Signal Processing
# 1.1 ~ Definitions and Terminology
### What is a differential equation?
- An equation containing the derivatives of one or more unknown functions (or dependent variables), with respect to one or more independent variables, is said to be a differential equation(DE). 

### Ways of Solving Equations:
##### Subtraction
$$
y + 5 = 13 \implies y = 8
$$
##### Factoring
$$
y^2 + 2y + 1 = 0 \implies (y+1)^2 = 0 \implies y = -1
$$

##### Quadratic Formula
##### Numerical Techniques

# Differential Equations Examples
$$
\frac{dy}{dx} = x^2
$$
$$
y = \phi(x) = \frac{1}{3}x^3 + C
$$
$$
y' - y = 0 \implies y' = y \implies y = \phi(x) = Ce^x
$$
$$
y'' + y = 0 \implies y'' = -y \implies y = \phi(x) = a\sin(x)
$$
### Definition 
[Differential Equations](differential-equations.md) - An equation involving derivatives of one or more functions (aka dependent variables) with respect to one or more independent variables.

###### Example 1:
$$
\frac{dy}{dx} + 5y = e^x \equiv y' + 5y = e^x
$$

In this example $y'$ and $5y$ are the dependent variables, and $e^x$ is the independent variable. 

###### Example 2:
$$
u(x, y) = \frac{\partial^2(u)}{\partial(x)^2} - \frac{\partial^2(u)}{\partial(y)^2} = 2 \frac{\partial(y)}{\partial(x)}
$$

### Classification by Type
[ODE](ordinary-differential-equations.md) - Ordinary Differential Equation
	- Has only one independent variable and ordinary derivatives
	- F(x,y,y',y'',...,y^n) = 0
		- Only one independent variable (x), y^n is the nth derivative of y. 
[PDE](partial-differential-equation) - Partial Differential Equation 
	- Has two or more independent variables and partial derivatives

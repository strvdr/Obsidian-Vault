### Definition:
Differential Equations - An equation containing the derivatives of one or more unknown functions (or dependent variables), with respect to one or more independent variables, is said to be a differential equation. 

To talk about Differential Equations, we shall classify them according to:
- Type - If a differential equation contains only ordinary derivatives of one or more unknown functions with respect to a single independent variable, it is said to be an ordinary differential equation (ODE). An equation involving partial derivatives of two or more independent variables is called a partial differential equation (PDE).
- Order - The order of a differential equation (either ODE or PDE) is the order of the highest derivative in the equation.
$$
\frac{d^2y}{dx^2} + 5\left( \frac{dy}{dx} \right)^3 - 4y = e^x
$$
$\frac{d^2y}{dx^2}$ In this example, is of the second order and $\left( \frac{dy}{dx} \right)^3$ is of the first order. In Example 1, the first and third equations are second-order PDEs. A first-order ordinary differential equation is sometimes written in the differential form:
$$
M(x,y) dx + N(x,y) dy = 0
$$
- Linearity - 

#### Example 1: Types of Differential Equations
The following equations are examples of ordinary differential equations:
$$
\frac{dy}{dx} + 5y = e^x
$$
$$
\frac{d^2y}{dx^2} - \frac{dy}{dx} + 6y = 0
$$
$$
\frac{dx}{dt} + \frac{dy}{dt} = 2x + y
$$
As shown in the last example, ODE's can contain more than one unknown function. 

The following equations are partial differential equations:
$$
\frac{\partial^2(u)}{\partial(x)^2} + \frac{\partial^2(u)}{\partial(y)^2} = 0
$$
$$
\frac{\partial^2(u)}{\partial(x)^2} = \frac{\partial^2(u)}{\partial(t)^2} - 2\frac{\partial(u)}{\partial(t)}
$$
$$
\frac{\partial(u)}{\partial(y)} = - \frac{\partial(v)}{\partial(x)}
$$
Note that in the third equation, there are two unknown functions and two independent variables in the PDE. This means that $u$ and $v$ must be functions of two or more independent variables.

#### Example 2: Differential Form of a First-Order ODE
If we assume that y is the dependent variable in a first-order ODE, then recall from Calculus that the differential $dy$ is defined to be $dy = y'dx$. 
- By dividing the differential dx, an alternative form of the equation $(y-x) dx + 4x dy = 0$ is given by:
$$
y - x + 4x\left( \frac{dy}{dx} \right) = 0
$$

- Or, equivalently: 
$$
4x \left( \frac{dy}{dx} \right) + y = x
$$
- B
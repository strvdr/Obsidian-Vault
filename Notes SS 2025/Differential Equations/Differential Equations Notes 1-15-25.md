### Models of Differential Equations
#### Steps: 
1) State assumptions
2) Decide on your independent variable and dependent variables;  any related parameters
3) Derive the Differential Equation

### Exponential Growth Model
1) The assumption is that growth rate of some quantity is proportional to it's size (e.g. population, investments)
2) Independent variable is t (time) 
3) Dependent variable is p (population)
4) Constant parameter, $k > 0$, is the constant of proportionality aka growth rate
$$
\frac{dP}{dt} \propto P
$$
$$
\frac{dP}{dt} = kP
$$
 $$
DE: P' = kP
$$
 $$
\text{Solution: Family of } P = Ae^{kt}
$$
$$
\text{Verify: } P' = Ake^{kt}
$$
$$
= kAe^{kt}
$$
$$
= kP
$$
New 1) Modification: Add poison to the bacteria
- Bacteria will kill population at a constant rate, h > 0

New 2) Constant Rate h > 0, parameter, constant

$$
\frac{dP}{dt}=kP - h
$$
New DE:
$$
P' = kP - h
$$

## Chapter 2: Solving n=1 ODE's
$$
\frac{dy}{dx}=f(x,y)
$$
### Section 2.1: Slope Fields
- Slope fields give us valuable information about the solution without actually finding a solution. 
- e.g.
$$
\text{f is continuous} \implies \frac{{\partial f}}{\partial y} \text{ is continuous}
$$


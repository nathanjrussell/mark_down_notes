#Example 1
Solve the equation below
$$11^{3x} - e^{4x-8} = 0$$
In this instance we can modify the equation to make both sides of the equation and exponential expression shown below.
$$11^{3x} = e^{4x-8}$$
Notice that the left and right side of the equation have different bases.  More to the point, neither base is an integer power of the either.  It would be feasible to express one base as a power of the other one.  This is precisely the scenario for the use of logarithms.

Given that logarithms are one-to-one functions, meaning $\ln(a) = \ln(b)$ implies that $a=b$ we can assume the following.
$$11^{3x} = e^{4x-8} \implies \ln(11^{3x}) = \ln(e^{4x-8})$$
The new equation to solve is the following
$$\ln(11^{3x}) = \ln(e^{4x-8})$$
At first, this may not seem like an improvement with respect to difficulty.  However, the property of logarithms that states $\ln_a(x^y) = y \ln_a(x)$ will be very helpful in this situation.  The exponents will come down as a product outside the logarithm. This is demonstrated below.
$$3x \cdot \ln(11) = (4x-8) \cdot \ln(e)$$
One obvious question that arises is why we choose to use the natural logarithm.  We should always choose a logarithm that has a base equal to one of the exponential expression bases.  We could have chosen to use $\log_3$ (log base 3).

Recall that the base of the natural logarithm is base $e$ (Euler's constant). As a result we have the following
$$\ln(e) = \log_e(e) = 1$$
This makes our equation slightly easier since $\ln(e) = 1$
$$3x \cdot \ln(11) = 4x-8$$
We must isolate the $x$ terms on one side of the equal sign.
$$3x \cdot \ln(11) - 4x = -8$$
We can now factor out the $x$ on the left side of the equation
$$x (3 \cdot \ln(11) - 4) = -8$$
Notice that the expression $3 \cdot \ln(11) - 4$ is just a value.  It has a complicated form to it, but it is still just a number.  That means we can divide both sides by that value.
$$\frac{x (3 \cdot \ln(11) - 4)}{3 \cdot \ln(11) - 4} = \frac{-8}{3 \cdot \ln(11) - 4}  $$
Notice the left hand side simplifies to $x$.  This results in the following
$$x = \frac{-8}{3 \cdot \ln(11) - 4}  $$
As a result, we have our solution to the equation.  We have solved for $x$.
Restate the result in terms of the problem.

The equation $11^{3x} - e^{4x-8} = 0$ implies $x = \frac{-8}{3 \cdot \ln(11) - 4} $

Mathematicians always want to use exact values when possible.  Notice the value of $x$ is just a number expressed in a strange, but exact, form.
$$x = \underbrace{\frac{-8}{3 \cdot \ln(11) - 4}}_{\text{exact}}  \approx \underbrace{-2.5049427}_{\text{approximate}} $$

If you are interested in showing off your mathematical manipulation skills, you can swap the binomial on the bottom to negate the negative on the top.  This is demonstrated below.
$$x = \frac{-8}{-(4-3\ln(11))}= \frac{8}{4-3\ln(11)}$$
This results in the slightly refined exact and simplified answer below.
$$x=\frac{8}{4-3\ln(11)}$$

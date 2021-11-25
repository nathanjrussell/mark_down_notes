#Example 1
Solve the equation below.
$$\log_7(x^2 - 21) - \log_7(4x) = 0$$
By manipulating the equation we have the equivalent equation shown below.
$$\log_7(x^2 - 21) = \log_7(4x)$$
By appealing to the one-to-one nature of logarithms where
$$\log_a(x) = \log_b(y) \implies x=y$$
it must be the case that
$$\log_7(x^2 - 21) = \log_7(4x) \implies x^2-21 = 4x$$
Now our problem has been reduced to solving the equation below.
$$x^2-21 = 4x$$
This is a simple quadratic equation.  Setting the equation in standard form we have the following
$$x^2-4x-21 = 0$$
The left hand side can be factored to give the following
$$(x+3)(x-7) = 0$$
By appealing to the zero factor property we have the following
$$\begin{align}
x+3 &= 0 \implies x=-3 \\
x-7 &= 0 \implies x = 7
\end{align}$$
At this point, we have two solution **CANDIDATES**.  Keep in mind, the input to logarithms may not be negative.  We must test all solution **CANDIDATES** in the inputs of the logarithms to verify a negative number is not passed into a logarithm.

We must verify the solutions make the following true
$$\begin{align}
x^2-21 &> 0 \\
4x &>0
\end{align}$$
Testing our solution **candiates**
####Test Solution Candidate $x = -3$
$$\begin{align}
x^2-21 &\implies (-3)^2-21 = 9-21 = -12 \leq 0 \text{ (not feasible)}  \\
4x &\implies 4(-3) = -12 \leq 0 \text{ (not feasible)}
\end{align}$$
The solution candidate $x=-3$ is not a feasible solution.  It makes the logarithm expression $\log_7(x^2-21) = \log_7(-12)$ have a negative input.

####Test Solution Candidate $x=7$
$$\begin{align}
x^2-21 &\implies (7)^2-21 = 49-21 = 28 >0 \text{ (feasible)}  \\
4x &\implies 4(7) = 28 > 0 \text{ (feasible)}
\end{align}$$
The solution candidate $x=7$ is a feasible solution.  It does not make the input of any logarithm a negative value.

Combine the results and restate in terms of the original problem.
The equation $\log_7(x^2 - 21) - \log_7(4x) = 0$ only has one solution, namely $x=7$.

#Example 2
Solve the equation below. Assume $\log(x)$ has base 10.
$$\log(x) = 1- \log(x-9)$$
Notice the equation can be manipulated to create the equivalent equation below.
$$\log(x) + \log(x-9) = 1$$
Using the properties of logarithms, the sum of logarithms can be rewritten as a product inside one logarithm.  This is demonstrated below.
$$\log(x\cdot(x-9)) = 1$$
Expanding the multiplication creates the following
$$\log(x^2-9x) = 1$$
If both sides of the equation contained a single logarithm, then we could simply set the inputs equal by appealing to the one-to-one nature of logarithms.  Luckily, this is possible given that the right hand side is 1.  This is demonstrated by the following.
$$\log_a(a) = 1$$
In this specific case we will use the following
$$\log(10) = 1$$
This translates our equation into the equivalent expression below.
$$\log(x^2-9x) = \log(10)$$
Now we can appeal to the one-to-one nature of logarithms.
$$\log(x^2-9x) = \log(10) \implies x^2-9x = 10$$
Our problem is now reduced to solving the equation below.
$$x^2-9x = 10$$
This is simply a quadratic equation. Setting the quadratic to standard form gives the following
$$x^2-9x-10 = 0$$
The left hand side can be factored resulting in the equation below.
$$(x+1)(x-10) = 0$$
Appealing to the zero factor property we get the following solution **candidates**
$$\begin{align}
x+1 &= 0 \implies x=-1 \\
x-10&=0 \implies x=10
\end{align}$$
These are called solution **candidates** because solutions can not result in the input of a logarithm being negative. As a result, solutions must make the expressions below true.
$$\begin{align}
x &> 0 \\
x-9 &>0
\end{align}$$
####Testing $x=-1$
$$\begin{align}
x &\implies -1 \leq 0 \text{ (not feasible)}  \\
x-9 &\implies (-1-9) = -10 \leq 0 \text{ (not feasible)}
\end{align}$$
This solution is not feasible because it makes the input of a logarithm zero or less.
####Testing $x=10$
$$\begin{align}
x &\implies 10 > 0 \text{ (feasible)}\\
x-9 &\implies (10-9) = 1 > 0 \text{ (feasible)}
\end{align}$$
This solution is feasible because it does not allow the input of a logarithm to be zero or less.
Combining the results and restated in terms of the original problem.

The equation $\log(x) = 1- \log(x-9)$ implies $x=10$
The only solution to the equation is $x=10$.

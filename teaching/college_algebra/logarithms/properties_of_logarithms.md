#Properties of Logarithms
Most of the properties of logarithms can be understood when analyzed as exponential expressions.

The the purpose of this tutorial, all input values for logs will be considered greater than zero and the base values will be greater than zero.
***
####Property 1 :: $\log_a(a) = 1$
This property is fairly straight forward if we ask ourselves..."What power do I raise $a$ to get $a$".  Anytime a value is raised to the first power, the result in the same value. Below are some examples.
$$\begin{align}
\log_2(2) &= 1 \\
\log_{200}(200) &= 1 \\
\log_{0.5}(0.5) &= 1 \\
\log_{\frac{7}{5}}\left( \frac{7}{5} \right) &= 1
\end{align}
$$

***
####Property 2 :: $\log_a(b^x) = x \cdot \log_a(b)$
This is among the most useful properties of logarithms. Notice the variable $x$ comes out of the exponent position to simply be multiplied out front.  This is the fundamental property that allows logarithms to help solve exponential equations. Below are some examples.
$$\begin{align}
\log_2 \left( 5^7 \right) &= 7 \cdot \log_2(5) \\
\log_{900} \left(17^{57} \right) &= 57 \cdot \log_{900}(17)
\end{align}$$
***
####Property 3 :: $\log_a(x \cdot y) = \log_a(x) + \log_a(y)$
Inputs that can be expressed as products inside a logarithm translate to the sum of logarithms.  This can often be very usefu in solving logarithmic equations. Below is an example.
$$\begin{align}
\log_7(2 \cdot 3) &= \log_7(2) + \log_7(3)
\end{align}$$
****
####Property 4 :: $\log_a \left( \frac{x}{y} \right) = \log_a(x) - \log_a(y)$
This is a similar property to the previous property.   Below is an example.
$$\begin{align}
\log_5 \left( \frac{8}{11} \right) &= \log_5(8) - \log_5(11)
\end{align}$$
***
####Property 5 :: $a ^ {\log_a(x)} = x$
This property may appear a little strange looking, but it actually comes in handy at times.  The exponent expression, namely $\log_a(x)$, answers the question..."What power do we raise a to get $x$".  Notice that the full expression raises $a$ to that value.  As a result, it is not surprise that we get the value of $x$.  Below is an example.
$$7^{\log_7(5)} = 5$$
***
####Property 6 :: $\log_a(b) = \frac{\log_c(b)}{\log_c(a)}$
#####Change Of Base Property
Notice the left-handside of the equation does not contain the value $c$ anywhere.  This implies that a logarithm can be expressed as a quotient of any other logarithm.  This property is known as the change of base property.  Below are some examples.
$$\begin{align}
\log_7(5) &= \frac{\log_9(5)}{\log_9(7)} \\\\
\log_2(17) &= \frac{\log_3(17)}{\log_3(2)}
\end{align}$$
***
####Common Logarithms And Notations
There are some standardized conventions associated with logarithms. Two logarithms are written without a base.
$$\begin{align}
\ln(a) &= \log_e(a) \\
\log(a) &= \log_{10}(a)
\end{align}$$

#####The Natural Logarithm :: $\ln(a)$
Given the change of base property, it is possible to express all other logarithms using a single logarithm.  It is common in scientific calculations for the natural logarithm $\ln(a)$ to be exclusively used.  In fact, many programming languages like C the natural log is given as $\log$. However, this is a convention reserved limited to programming languages and some academic research. In most cases, it does not matter which logarithm is used as long as it is used consistently.

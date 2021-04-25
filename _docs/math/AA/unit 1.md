---
title: Sequence and Series
description: Unit 1 of Math AA HL
---

Sequence and Series
===================

Sequence, Series, and Sigma Notation
------------------------------------

A sequence is a list of number that is written in a defined order. A
sequence usually follows a predefined list of rules. The numbers of the
sequence are called terms. Sometimes, the sequence is also referred to
as a progression.

The Sigma Notation is way to write the addition of a sequence. Sigma
notation is written below, $a,b,c$ are the variables.

$$\sum_{n=a}^{b} c$$

$a$ represents the starting value of n. $b$ represents the largest value
of n. $c$ is the equation that is to be added.

Arithmetic and Geometric Sequences and Series
---------------------------------------------

### Arithmetic Sequence

An arithmetic sequence is a series of numbers in a linear relationship.
Modeled by the equation: $$U_n = U_1 + (n-1)d$$

Where $U_n$ represents the nth term. $U_1$ represents the first term.
And $d$ represents the difference between each term.

The sum of an arithmetic sequence is modeled by this equation:
$$S_n = n\cdot\frac{2U_1+(n-1)d}{2}$$ This equation averages the first
and last term, then multiplies the average by $n$ numbers of terms.

### Geometric Sequences and Series

An geometric sequence is a series of numbers in a exponential
relationship. Modeled by: $$U_n = U_1 \cdot r^(n-1)$$

Where $U_n$ is the nth term of the sequence, $U_1$ is the first term is
the sequence, and $r$ is the common ratio.

If the common ratio is 1, then the sequence will be a uniformed
sequence. If the common ratio is 0, then all the sequence will start
with a value, and continue with all zeros. If the common ratio is
negative, then the sequence will oscillate between negative and
positive.

The sum of a geometric sequence can be modeled by:
$$S_n = \frac{U_1(1-r^n)}{1-r}; \; r\neq1$$

An infinite geometric series is convergent when the sum of the series is
a finite value. If a geometric series is not convergent, it is
divergent. Generally, the common ratio of the geometric sequence have to
be less that 1 but larger than 0 in order to be convergent.

The sum of a infinite convergent geometric sequence can be modeled by:
$$S_\infty = \frac{U_1}{1-r}$$

Proof
-----

A proof is a way to mathematically validate a statement.

### Direct Proof

A direct proof is a way of showing the truth of a given statement by
constructing a series of reasoned connected established facts. First, we
identify the statement. Then, we use axioms, theorems, to make
deductions that prove the conclusion of your statement to be true.

### Proof by Contradiction

If a logical reasoning is true, than the contrapositive is false. First,
we identify the implication of the statement. Then assume the
implication is false. Use axioms, theorems, etc to arrive at a
contradiction. This proves that the original statement is true.

### Proof by Induction

First, we find the starting point of a process. This is called the basic
step. Then, we continue with the basic step until we reach the inductive
step. Finish proof.

Counting Principles and the Binomial Theorem
--------------------------------------------

### Factorial Notation

The factorial notation ($!$) is a way to denote the multiplication of a
certain length of integers. Factorial notation tends to result in very
large numbers.

$$n! = n \cdot (n-1) \cdot (n-2) \cdot \cdots \cdot 3 \cdot 2 \cdot 1$$

A division of a bigger factorials by a smaller factorial can be down in
the following method: $$\begin{aligned}
	\frac{5!}{3!} &= \frac{5 \cdot 4 \cdot 3 \cdot 2 \cdot 1}{3 \cdot 2 \cdot 1} \\
				  &= 5 \cdot 4 \end{aligned}$$

### Permutation

Permutation is written is the format of:
$${}^{n}\!P_{k} = \frac{n!}{(n-k)!}$$ Where $n$ is the objects to chose
from and $r$ is the number of objects chosen.

Permutation is used in a situation where order of arrangement matters.
This also means repetition of same sequence in different order is
allowed.

### Combinations

Combinations is written in the format:
$${}^{n}C_{r} = \frac{n!}{r!(n-r)!}$$ Where $n$ is the objects to chose
from and $r$ is the number of objects chosen.

Combination is used in a situation where order does not matter. This
also means that repetitions of the same sequence is not allowed.

### Binomial Theorem

Binomial Theorem models the resulted equation from $(a+b)^n$.
$$(a+b)^n = {}^{n}C_{0} a^n b^0 + {}^{n}C_{1} a^{n-1} b^1 + {}^{n}C_{2} a^{n-2} b^2 + \cdots + {}^{n}C_{r} a^{n-r} b^r + \cdots + {}^{n}C_{n} a^0 x^n$$
Where $r$ is the r-th term inside the sequence.

Note, the prefix for each term (Combination value) also corresponds to
Pascal's Triangle.

  ------- --- --- --- --- ---- ---- ---- ---- ---- --- --- --- ---
  $r=0$                              1                         
  $r=1$                         1         1                    
  $r=2$                    1         2         1               
  $r=3$                1        3         3         1          
  $r=4$            1       4         6         4        1      
  $r=5$        1       5        10        10        5       1  
  $r=6$    1       6       15        20        15       6       1
  ------- --- --- --- --- ---- ---- ---- ---- ---- --- --- --- ---

We can find the specific term from binomial expansion by using this
expression: $${}^{n}C_{r} a^r b^{n-r}$$

A more generalized Binomial Theorem that supports negative exponents can
be found here:
$$(1+x)^a = 1 + ax + \frac{a(a-1)}{2!} + \frac{a(a-1)(a-2)}{3!} + \cdots + \frac{a(a-1)(a-2)\cdots(a-r+1)}{r!} x^r + \cdots$$
We can use this expression to manually calculate roots of a number.
$$\begin{aligned}
	\sqrt{3} = (1 + 2)^{\frac{1}{2}}\end{aligned}$$

Financial Applications
----------------------

Geometric Sequences is sometimes used to calculate the interest of a
deposit or similar circumstances. A equation to model this is:

$$FV = PV \cdot ( 1 + \frac{r}{100k} )^{kn}$$

Where $FV$ is the future value, $PV$ is the present value, $n$ is the
number of years, $k$ is the compound periods per year, and $r$ is the
nominal annual rate of interest in percent. If $r$ is negative, then
there is exponential decay.

Functions
=========

Functional Relationships
------------------------

The set of x-values that make up a function is called the domain. The
set of y-values that make up a function is called the range.

An equation is a function only when $f$ acts on all elements of the
domain, and each domain pairs with one and only one range element. This
test is called the vertical line test. If one were to drawn an
infinitely long vertical line on any x domain, then the vertical line
will only intersect the function at one point.

There is a similar test called the horizontal line test. In which a
infinitely long horizontal line is drawn on any $y$ range, then the
horizontal line will only intersect the function at one point. A
function must pass the horizontal line test in order to have an inverse.

### Odd and Even Functions

An even function is a function that is symmetric over the $y$ axis. Or
in other words, $f(x) = f(-x)$.

An odd function is a function that is symmetric over the line $y=-x$. Or
in other words, $f(x) = -f(-x)$

### Mapping

A one to one function is where every point of the domain corresponds to
one point on the range. A one to many function is where every point of
the domain corresponds to many points on the range, this if not a
function. A many to one function is where many points of the domain
corresponds to the same point on the range, this function does not have
an inverse function. A many to many function is where many points on the
domain corresponds to many points on the range, this is not a function.

### Self Inverse

If the inverse of a function is itself, it is a self inversing function.
$$f^{-1}(x) = f(x)$$

Special Functions and Their Graphs
----------------------------------

### Domain and Range of Common Functions

$$\begin{aligned}
{3}
	y &= mx + b \qquad &&x \in R,\; y \in R\\
	y &= ax^2 + bx + c \qquad &&x \in R,\;
	\begin{dcases}
		\textrm{if } a > 0, y \ge k \\
		\textrm{if } a < 0, y \le k
	\end{dcases} && \qquad \textrm{where } (h,k) \textrm{ is the vertex}\\
	y &= a^x \quad (a>0,\; a\neq1) \qquad && x \in R,\; y > 0 \qquad && (y = 0 \textrm{ is an asymptote}) \\
	y &= \log_a{x} \quad (a>0,\;a\neq1) \qquad && x > 0,\; y \in R \qquad && (x=0 \textrm{ is an asymptote}) \\
	y &= \frac{1}{x} \quad && x \neq 0,\; y \neq 0 \qquad && (x=0 \textrm{ and } y=0 \textrm{ are the asymptote}) \\
	y &= \frac{ax+b}{cx+d} \quad && x \neq -\frac{d}{c},\; y\neq \frac{a}{c} \\
	y &= \sqrt{x} \quad && x \ge 0,\; y \ge 0 \\
	y &= \sin{x} \quad && x \in R, \; -1 \le y \le 1 \\
	y &= \cos{x} \quad && x \in R,\; -1 \le y \le 1 \\
	y &= \tan{x} \quad && x \neq \frac{\pi}{2}+k\pi,\;k \in Z,\quad y \in R \\\end{aligned}$$

In general, for the domain of each equation, watch out for vertical
asymptotes and undefined numbers ($\sqrt{-1},\; \frac{1}{0}$).

For the range of each equation, watch out for horizontal asymptotes,
turning points/vertex, and domain limitations.

### Quadratic Functions

#### Forms of Quadratics

A quadratic function have 3 forms: Standard form, Vertex form, and
Intercept form.

$$\begin{aligned}
	y &= ax^2 + bx + c \\
	y &= a(x-h)^2 + k \\
	y &= a(x-p)(x-q) \end{aligned}$$

In the standard form, $a$ defines to concavity of the function. If
$a>0$, the quadratic concaves up, if $a<0$, the quadratic concave down.
$c$ represents the x-intercept of the quadratic.

In vertex form, $(h,k)$ is the vertex of the quadratic. A vertex is the
turning point of the quadratic, it is also where the axis of symmetry
lies. The quadratic is mirrored across the axis of symmetry.

In the intercept form, $p$ and $q$ are the x intercepts (or zeros) of
the function.

#### Equations

The equation for the axis of symmetry is: $$x = -\frac{b}{2a}$$

The sum of roots of a quadratic is: $$(\alpha+\beta) = -\frac{b}{a}$$

The product of roots of a quadratic is:
$$(\alpha \cdot \beta) = \frac{c}{a}$$

#### Finding the Roots

There are four ways to find the roots of a quadratic. You can graph it
using the GDC. You can use the quadratic formula. You can use complete
the square.

The quadratic formula is listed below:
$$x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$

$\Delta = b^2-4ac$ is the discriminant. If:

-   $\Delta > 0$, the function have 2 real roots

-   $\Delta = 0$, the function have 1 unique real root

-   $\Delta < 0$, the function have no real roots.

To factor, simply factor the quadratic into the intercept form using the
sum and product of roots equations.

To complete the square, start with the equation in standard from. Set
$y$ to zero. Then, remove the coefficient of x (by factoring it out).
Afterwards, use the property $(a+b)^2  = a^2 + 2ab + b^2$ to factor the
equation into vertex form.

### Rational Function

A function is rational function if its is made up of the dividing of two
polynomials. $$y = \frac{f(x)}{g(x)}$$ Where $f(x)$ and $g(x)$ are the
two polynomials.

The reciprocal function $y=\frac{1}{x}$ is a polynomial.

There is four important points on a polynomial. These are the:

-   Horizontal Asymptote

-   Vertical Asymptote

-   X-Intercept

-   Y-Intercept

We generally use plot these points/lines first before drawing a
polynomial.

To find the horizontal asymptote, there is 3 possibility.

-   If $f(x)$ has the higher degree, then there is no horizontal
    asymptote

-   If $g(x)$ has the higher degree, then the horizontal asymptote is
    $y=0$

-   If $g(x)$ and $f(x)$ have the same degree, then the horizontal
    asymptote is $y=\frac{f_n}{q_n}$, where $f_n$ and $q_n$ are the
    leading coefficient of $f(x)$ and $p(x)$.

The vertical asymptote is when $g(x) = 0$. Thus, find the roots of
$g(x)$.

To find the x-intercept, find the roots of $f(x)$.

The y-intercept is at point $\frac{b}{c}$. Where $b$ is the constant of
$f(x)$ and $c$ is the constant of $g(x)$.

#### Drawing Rational Function

After plotting all four points/lines, plot a sign diagram. Where the
roots of $f(x)$ and $g(x)$ are the numbers. This sign diagram represents
the domain of the rational function. Find whether the value of the y is
positive or negative in each section of the sign diagram.

Use this information to plot the rational function.

### Absolute Value Functions and Equations

$$|a| = 
	\begin{dcases}
		\;\;\;a,\; a \ge 0 \\
		-a,\; a \le 0 \\
	\end{dcases}$$

#### Useful Features of An Absolute Function

$$\begin{aligned}
	|a| &\ge 0 \\
	|-a| &= |a| \\
	|ab| &= |a||b| \\
	|a+b| &\le |a| + |b| \\
	|a-b| &\ge |a| - |b| \\\end{aligned}$$

#### Removing Absolute Value

You can add a $\pm$ on the other side. $$\begin{aligned}
	|x| &= y \\
	x &= \pm y\end{aligned}$$

Or square both sides: $$\begin{aligned}
	|x| &= y \\
	x^2 &= y^2\end{aligned}$$ Note, squaring changes the domain. Recheck
you answers after squaring.

#### Inequalities

You cannot add $\pm$ in a inequality. As $\pm$ means potentially
flipping the inequality. Thus, we split the equation up into two parts.

$$\begin{aligned}
	y &> |x| \\ 
	y < x \; &\textrm{ or } \; y > x \\\end{aligned}$$

There are some short cuts. $$\begin{aligned}
	x < |a| &= -a < x < a \\
	x > |a| &= x > a \textrm{ or } x < -a \end{aligned}$$

Operations with Function
------------------------

To do functional operation, put the function in quotes, then do
operations.

$$\begin{aligned}
	f(x) &= x+5 \\
	g(x) &= 3x \\
	f(x) \cdot g(x) &= (x+5)(3x)\end{aligned}$$

### Composite Functions

$$\begin{aligned}
	f \circ g(x) = f(g(x))\end{aligned}$$ In order for the composite
function exist, the range of $g(x)$ has to fit within the domain of
$f(x)$. Else, some values may be undefined.

The range of $f \circ g(x)$ is a subset of $f(x)$.

### Identity Function

The identity function is a function which when composed with another
function, it remains unchanged. $$f \circ g(x) = f(x)$$ $g(x)$ is an
identity function.

Generally, $f(x) = x$ is an identical function.

### Inverse

An inverse function is a function that returns the identity function
when composited with another function. $$f(x) \circ g(x) = x$$ We often
write this function in special notation: $f^{-1}(x)$

To find the inverse function of a certain function, swap the x and y
values of the function. Then solve for y. $$\begin{aligned}
	f(x)    & = \frac{4x}{2x-2} \\
	x       & = \frac{4y}{2y-2} \\
	2yx -2x & = 4y \\
	2yx-4y  & = 2x \\
	y(2x-4) & = 2x \\
	y       & = \frac{2x}{2x-4} \\
	f^{-1}(x) & = \frac{2x}{2x-4}\end{aligned}$$

Note, when calculating the point where the inverse of a function
intersect with the function, we can use the equation: $f(x) = x$ to find
the point of intersection.

The domain of the inverse function is the range of the original
function. The range of the inverse function is the domain of the
original function.

### Reciprocal Function

The reciprocal function is $$f(x)=\frac{1}{x}$$

When graphing the reciprocal of a function, there are several points
important points.

-   all points at $y=1$ stays unchanged

-   roots of the original function becomes asymptote

-   positive numbers stays positive, negative numbers stay negative

-   $y$ values above $|1|$ is stretched upwards, while $y$ values below
    $|1|$ shrinks

Transformations
---------------

There is three types of transformation. Translation, stretch, and
reflection.

$$f(x) \Rightarrow A \cdot f(Bx + C) + D$$ Where:

-   $A$ is vertical stretch.

-   $\frac{1}{B}$ is horizontal stretch.

-   $-C$ is horizontal translation.

-   $D$ is vertical translation.

Sometimes, we would use a translation vector: $$\begin{pmatrix}
		a \\
		b
	\end{pmatrix} \rightarrow f(x-a)+b$$

### Translation

$$\begin{aligned}
{2}
	&f(x+a) \qquad && f(x) \textrm{ shifts to the left by } a \textrm{ units } \\
	&f(x-a) \qquad && f(x) \textrm{ shifts to the right by } a \textrm{ units } \\
	&f(x)+a \qquad && f(x) \textrm{ shifts upwards by } a \textrm{ units } \\
	&f(x)-a \qquad && f(x) \textrm{ shifts downwards by } a \textrm{ units }\end{aligned}$$

Be very careful, as adding inside the bracket will shift the function to
the *left*.

### Stretch

$$\begin{aligned}
{2}
	&f(ax) \qquad && f(x) \textrm{ is horizontally stretched by a factor of } \frac{1}{a} \\
	&f(\frac{x}{a}) \qquad && f(x) \textrm{ is horizontally stretched by a factor of } a \\
	&a \cdot f(x) \qquad && f(x) \textrm{ is vertically stretched by a factor of } a \\
	&\frac{1}{a} \cdot f(x) \qquad && f(x) \textrm{ is vertically stretched by a factor of } \frac{1}{a} \\\end{aligned}$$

Be very careful, as horizontal stretching by a factor of $a$ is actually
multiplying by a factor of $\frac{1}{a}$.

### Reflection

Multiplying the contents of a function by $-1$ can reflect the function
across the $x$ or $y$ axis.

$$\begin{dcases}
		f(x) \rightarrow f(-x) \qquad f(x) \textrm{ is reflected by y-axis } \\
		f(x) \rightarrow -f(x) \qquad f(x) \textrm{ is reflected by x-axis }
	\end{dcases}$$

### Modulus

Similar to reflection, adding an absolute value reflects all negative
values across an axis. $$\begin{dcases}
		f(x) \rightarrow f(|x|) \qquad f(-x) = f(x) \\
		f(x) \rightarrow |f(x)| \qquad -f(x) = f(x)
	\end{dcases}$$

Systems of Equations
--------------------

A system of equation means that there is multiple variables and multiple
equations. A system of equation with n variables will need n equations
to solve completely.

There is two ways to solve a system of equation: substitution or
elimination. In a systems of equation, combine two equations to
substitute or eliminate an equation. Keep repeating the step above until
you reach one answer. Use that answer to plug in, and solve for other
variables.

For system of equation with more than 2 equations, use the Gaussian
Elimination method. First, put the system of equation in matrix form.
Then manipulate the matrix until it become an identity matrix. You can
multiply each row by the same factor, and you can add a row by another
row.

$$\begin{aligned}
&\begin{dcases}
	2x + y + z = 7 \\
	x + 3y + 2z = 13 \\
	4x - 2y + 3z = 9
\end{dcases} \\ 
&\left[ \begin{array}{ccc|c}
	2 & 1 & 1 & 7 \\
	1 & 3 & 2 & 13 \\
	4 & -2 & 3 & 9 
\end{array} \right] \\
&\left[ \begin{array}{ccc|c}
	1 & 3 & 2 & 13 \\
	0 & 5 & 3 & 19 \\
	0 & 14 & 5 & 43 
\end{array} \right] \\
&\left[ \begin{array}{ccc|c}
	1 & 3 & 2 & 13 \\
	0 & 5 & 3 & 19 \\
	0 & 0 & 1 & 3
\end{array} \right] \\
&\left[ \begin{array}{ccc|c}
	1 & 3 & 0 & 7 \\
	0 & 1 & 0 & 2 \\
	0 & 0 & 1 & 3
\end{array} \right] \\
&\left[ \begin{array}{ccc|c}
	1 & 0 & 0 & 1 \\
	0 & 1 & 0 & 2 \\
	0 & 0 & 1 & 3
\end{array} \right] \\
&\begin{dcases}
	x = 1 \\
	y = 2 \\
	z = 3 \\
\end{dcases}\end{aligned}$$

Exponents and Logarithms
========================

Exponents
---------

### Identities

Exponents have some simply identities.

$$\begin{aligned}
	\begin{dcases}
		a^m \cdot a^n = a^{m+n} \\
		a^m \div a^n = a^{m-n} \\
	\end{dcases} \\
	\begin{dcases}
		a^m \cdot b^n = (ab)^m \\
		a^m \div a^m = (\frac{a}{b})^m \\
	\end{dcases} \\
	(a^m)^n &= a^{mn} \\
	a^0 &= 1 \\
	a^{\frac{1}{2}} &= \sqrt{a} \\
	a^{-m} &= \frac{1}{a^m} \\
	a^{\frac{m}{n}} &= \sqrt[n]{m}\end{aligned}$$

### Solving Exponents

When solving exponents, always look for similar base or similar
exponents.

Logs
----

$$\log_a{b}$$ $b$ has to be greater than or equal to 0.

### Identities

$$\begin{aligned}
	\begin{dcases}
	\log_a{b} = x \\
	a^x = b
	\end{dcases} \\
	\log_a{1} &= 0 \\
	a^{\log_a{x}} &= x \\
	\log_a{x} + \log_a{y} &= log_a{x\cdot y} \\
	\log_a{x} - \log_a{y} &= log_a{x\div y} \\
	\log_a{x^b} &= b\cdot\log_a{x} \\
	\log_{a^b}{x} &= \frac{1}{b}\cdot\log_a{x} \\
	\log_m{n} &= \frac{\log_x{n}}{\log_x{m}}\end{aligned}$$

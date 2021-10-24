---
title: Complex Numbers
description: Unit 2 of Math AA HL
---

# Quadratic Functions

## Forms of Quadratics

A quadratic function have 3 forms: Standard form, Vertex form, and X-Intercept form.

$$\begin{aligned}
	y &= ax^2 + bx + c \\
	y &= a(x-h)^2 + k \\
	y &= a(x-p)(x-q) \end{aligned}$$

In the standard form, $a$ defines to concavity of the function.
If $a>0$, the quadratic concaves up, if $a<0$, the quadratic concave down.
$c$ represents the x-intercept of the quadratic.

In vertex form, $(h,k)$ is the vertex of the quadratic.
A vertex is the turning point of the quadratic, it is also where the axis of symmetry lies. The quadratic is mirrored across the axis of symmetry.

In the intercept form, $p$ and $q$ are the x intercepts (or zeros) of the function.

## Equations

The equation for the axis of symmetry is: \
$$x = -\frac{b}{2a}$$

The sum of roots of a quadratic is: \
$$(\alpha+\beta) = -\frac{b}{a}$$

The product of roots of a quadratic is: \
$$(\alpha \cdot \beta) = \frac{c}{a}$$

## Finding the Roots

There are four ways to find the roots of a quadratic.
You can graph it using the GDC.
You can use the quadratic formula. You can use complete the square.

The quadratic formula is listed below: 

$$x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$$

$\Delta = b^2-4ac$ is the discriminant. If:
-   $\Delta > 0$, the function have 2 real roots
-   $\Delta = 0$, the function have 1 unique real root
-   $\Delta < 0$, the function have no real roots.

To factor, simply factor the quadratic into the intercept form using the sum and product of roots equations.

To complete the square, start with the equation in standard from.
Set $y$ to zero.
Then, remove the coefficient of x (by factoring it out).
Afterwards, use the property $(a+b)^2  = a^2 + 2ab + b^2$ to factor the equation into vertex form.

## Quadratic Inequalities

To solve the inequality algebraically, draw a number line.
First solve find all the roots of the equation, them plot it onto a line.
Find whether the values for the quadratic is positive or negative on each line segment.
Use the resultant number line to find the set of solutions.

A sign table can also be used as a substitute for the number line.
Where each root is written onto a column instead of a line.

# Complex Numbers

Traditionally, there are no solves for the square root of a negative number. 
However, we can consider this number to be _imaginary_ and use the assigned constant $i$ to represent it.
Using $i$, we can all roots of a quadratic, real or _complex_ (a number containing both real and imaginary parts).

$i = \sqrt{-1}$

## Powers of i

The powers of i is recurring. 

$$\begin{aligned}
	i^0 &= 1 \\
	i^1 &= \sqrt{-1} \\
	i^2 &= -1 \\
	i^3 &= -\sqrt{-1} \\
	i^4 &= 1
\end{aligned}$$

## Graphing

Often times, complex numbers will be plotted on a Cartesian graph, where the $x$ axis is the `real axis` and the $y$ axis is the `imaginary axis`.
The distance of the number to the origin is the `magnitude` (or `modulus`) of the complex number.
The magnitude is written in the notation $|z|$.
To find the magnitude, use the equation: 

$$|z| = r = \sqrt{a^2 + b^2}$$

Where $a$ is the real part of $z$ and $b$ is the imaginary part of $z$.
$a$ can be written as $\textrm{Re}(z)$ and $b$ can be written as $\textrm{Im}(z)$

The argument of a complex number is the slope of the magnitude. 

$$\textrm{arg}(z) = \theta = \tan^{-1}(\frac{b}{a})$$

The conjugate of a complex number is the complex with a negative imaginary part. 

$$z^* = a - bi$$
The addition of two conjugate number result in twice the real part.
The subtraction of two conjugate number result in twice the imaginary part.

## Format of Complex Numbers

There are several ways to write an imaginary numbers.
Each format has its own uses.

- __Cartesian Form:__ $z = a + ib$. 
- __Polar Form:__ $z = r(\cos \theta + i\sin \theta) = r \cdot \textrm{cis}(\theta)$
- __Euler Form:__ $z = re^{i\theta}$

# Polynomials

# Fundamental Theorem of Algebra

# Solving Equations and Inequalities

# Solving Systems of Linear Equations

A system of equation means that there is multiple variables and multiple equations.
A system of equation with $n$ variables will need $n$ equations to solve completely.

There is two ways to solve a system of equation: substitution or elimination.
In a systems of equation, combine two equations to substitute or eliminate an equation.
Keep repeating the step above until you reach one answer.
Use that answer to plug in, and solve for other variables.

For system of equation with more than 2 equations, use the _Gaussian Elimination_ method.
First, put the system of equation in matrix form.
Then manipulate the matrix until it become an identity matrix.

The rules of matrix are:
- you can multiple an entire row with a constant
- you can add a constant to an entire row
- you can add a row into another row

$$\begin{aligned}
&\begin{dcases}
	2x + y + z = 7 \\
	x + 3y + 2z = 13 \\
	4x - 2y + 3z = 9
\end{dcases} \\ 
=&\left[ \begin{array}{ccc|c}
	2 =& 1 & 1 & 7 \\
	1 =& 3 & 2 & 13 \\
	4 =& -2 & 3 & 9 
\end{array} \right] \\
=&\left[ \begin{array}{ccc|c}
	1 =& 3 & 2 & 13 \\
	0 =& 5 & 3 & 19 \\
	0 =& 14 & 5 & 43 
\end{array} \right] \\
=&\left[ \begin{array}{ccc|c}
	1 =& 3 & 2 & 13 \\
	0 =& 5 & 3 & 19 \\
	0 =& 0 & 1 & 3
\end{array} \right] \\
=&\left[ \begin{array}{ccc|c}
	1 =& 3 & 0 & 7 \\
	0 =& 1 & 0 & 2 \\
	0 =& 0 & 1 & 3
\end{array} \right] \\
=&\left[ \begin{array}{ccc|c}
	1 =& 0 & 0 & 1 \\
	0 =& 1 & 0 & 2 \\
	0 =& 0 & 1 & 3
\end{array} \right] \\
=&\begin{dcases}
	x = 1 \\
	y = 2 \\
	z = 3 \\
\end{dcases}
\end{aligned}$$

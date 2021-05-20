---
title: Functions
description: Unit 2 of Math AA HL
---

# Functional Relationships

The set of $x$-values that make up a function is called the domain.
The set of $y$-values that make up a function is called the range.

An equation is a function only when $f$ acts on all elements of the domain, and each domain pairs with one and only one range element.
This test is called the vertical line test.
If one were to drawn an infinitely long vertical line on any $x$ domain, then the vertical line will only intersect the function at one point.

There is a similar test called the horizontal line test.
In which a infinitely long horizontal line is drawn on any $y$ range, then the horizontal line will only intersect the function at one point.
A function must pass the horizontal line test in order to have an inverse.

## Odd and Even Functions

- An __even function__ is a function that is symmetric over the $y$ axis. $f(x) = f(-x)$.
- An __odd function__ is a function that is symmetric over the line $y=-x$. $f(x) = -f(-x)$

## Mapping

- __A one to one function__ is where every point of the domain corresponds to one point on the range.
- __A one to many function__ is where every point of the domain corresponds to many points on the range, this if not a function.
- __A many to one function__ is where many points of the domain corresponds to the same point on the range, this function does not have an inverse function.
- __A many to many function__ is where many points on the domain corresponds to many points on the range, this is not a function.

## Self Inverse

If the inverse of a function is itself, it is a self inversing function.

$$\begin{aligned} f^{-1}(x) = f(x) \end{aligned}$$

# Special Functions and Their Graphs

## Domain and Range of Common Functions

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

## Quadratics

Refer to Unit 3.1.

## Rational Function

A function is rational function if its is made up of the dividing of two polynomials.
$$y = \frac{f(x)}{g(x)}$$ Where $f(x)$ and $g(x)$ are the two polynomials.
The reciprocal function $y=\frac{1}{x}$ is a polynomial.

There is four important points on a polynomial. These are the: 
-   Horizontal Asymptote 
-   Vertical Asymptote 
-   X-Intercept 
-   Y-Intercept

We generally use plot these points/lines first before drawing a
polynomial.

To find the horizontal asymptote, there is 3 possibility. 
-   If $f(x)$ has the higher degree, then there is no horizontal asymptote
-   If $g(x)$ has the higher degree, then the horizontal asymptote is $y=0$ 
-   If $g(x)$ and $f(x)$ have the same degree, then the horizontal asymptote is $y=\frac{f_n}{q_n}$, where $f_n$ and $q_n$ are the leading coefficient of $f(x)$ and $p(x)$.

The vertical asymptote is when $g(x) = 0$.
Thus, find the roots of $g(x)$.

To find the $x$-intercept, find the roots of $f(x)$.

The $y$-intercept is at point $\frac{b}{c}$.
Where $b$ is the constant of $f(x)$ and $c$ is the constant of $g(x)$.

### Drawing Rational Function

After plotting all four points/lines, plot a sign diagram.
Where the roots of $f(x)$ and $g(x)$ are the numbers.
This sign diagram represents the domain of the rational function.
Find whether the value of the y is positive or negative in each section of the sign diagram.
Use this information to plot the rational function.

## Absolute Value Functions and Equations

$$|a| = 
	\begin{dcases}
		\;\;\;a,\; a \ge 0 \\
		-a,\; a \le 0 \\
	\end{dcases}$$

### Useful Features of An Absolute Function

$$\begin{aligned}
	|a| &\ge 0 \\
	|-a| &= |a| \\
	|ab| &= |a||b| \\
	|a+b| &\le |a| + |b| \\
	|a-b| &\ge |a| - |b| \\\end{aligned}$$

### Removing Absolute Value

You can add a $\pm$ on the other side.

$$\begin{aligned} |x| &= y \\ x &= \pm y\end{aligned}$$

Or square both sides:

$$\begin{aligned} |x| &= y \\ x^2 &= y^2\end{aligned}$$ 

Note, squaring changes the domain.
Recheck you answers after squaring.

### Inequalities

You cannot add $\pm$ in a inequality.
As $\pm$ means potentially flipping the inequality.
Thus, we split the equation up into two parts.

$$\begin{aligned} y &> |x| \\ y < x \; &\textrm{ or } \; y > x \\\end{aligned}$$

There are some short cuts. 

$$\begin{aligned} x < |a| &= -a < x < a \\ x > |a| &= x > a \textrm{ or } x < -a \end{aligned}$$

## Piecewise Functions

A piecewise function is made up of several smaller functions.
Below is an example of a piecewise function.

$$\begin{aligned} f(x) = \begin{dcases} {x}, &x \leq 0 \\ {2x}, &x < 0 \end{dcases} \end{aligned} $$

# Operations with Function

To do functional operation, put the function in quotes, then do operations.

$$\begin{aligned} &f(x) = x+5 \\ &g(x) = 3x \\ f(x) &\cdot g(x) = (x+5)(3x) \end{aligned}$$

## Composite Functions

$$\begin{aligned} f \circ g(x) = f(g(x))\end{aligned}$$ 

In order for the composite function exist, the range of $g(x)$ has to fit within the domain of $f(x)$.
Else, some values may be undefined.

The range of $f \circ g(x)$ is a subset of $f(x)$.

## Identity Function

The identity function is a function which when composed with another function, it remains unchanged.
If $f \circ g(x) = f(x)$, $g(x)$ is an identity function.
Generally, $f(x) = x$ is an identical function.

## Inverse

An inverse function is a function that returns the identity function
when composited with another function. 

$$f(x) \circ g(x) = x$$ 

$g(x)$ is the inverse function of $f(x)$.
We often write this function in special notation: $f^{-1}(x)$

To find the inverse function of a certain function, swap the $x$ and $y$ values of the function. Then solve for $y$.

$$\begin{aligned}
	f(x)    & = \frac{4x}{2x-2} \\
	x       & = \frac{4y}{2y-2} \\
	2yx -2x & = 4y \\
	2yx-4y  & = 2x \\
	y(2x-4) & = 2x \\
	y       & = \frac{2x}{2x-4} \\
	f^{-1}(x) & = \frac{2x}{2x-4}
\end{aligned}$$

Note, when calculating the point where the inverse of a function intersect with the function, we can use the equation: $f(x) = x$ to find the point of intersection.

The domain of the inverse function is the range of the original function.
The range of the inverse function is the domain of the original function.

## Reciprocal Function

The reciprocal function is:

$$f(x)=\frac{1}{x}$$

When graphing the reciprocal of a function, there are several points important points.
-   all points at $y=1$ stays unchanged 
-   roots of the original function becomes asymptote 
-   positive numbers stays positive, negative numbers stay negative 
-   $y$ values above $1$ is stretched upwards, while $y$ values below $1$ shrinks

# Function Transformations

There is three types of transformation. Translation, stretch, and reflection.

$$f(x) = A \cdot f(Bx + C) + D$$ 

Where: 
-   $A$ is vertical stretch. 
-   $\frac{1}{B}$ is horizontal stretch. 
-   $-C$ is horizontal translation. 
-   $D$ is vertical translation.

Sometimes, we would use a translation vector:

$$\begin{pmatrix} a \\ b \end{pmatrix} \rightarrow f(x-a)+b$$

## Translation

$$\begin{aligned}
	&f(x+a) \qquad && f(x) \textrm{ shifts to the left by } a \textrm{ units } \\
	&f(x-a) \qquad && f(x) \textrm{ shifts to the right by } a \textrm{ units } \\
	&f(x)+a \qquad && f(x) \textrm{ shifts upwards by } a \textrm{ units } \\
	&f(x)-a \qquad && f(x) \textrm{ shifts downwards by } a \textrm{ units }\end{aligned}$$

Be very careful, as adding inside the bracket will shift the function to the _left_.

## Stretch

$$\begin{aligned}
	&f(ax) \qquad                  && f(x) \textrm{ is horizontally stretched by a factor of } \frac{1}{a} \\
	&f(\frac{x}{a}) \qquad         && f(x) \textrm{ is horizontally stretched by a factor of } a \\
	&f(x) \cdot a\qquad            && f(x) \textrm{ is vertically stretched by a factor of } a \\
	&f(x) \cdot \frac{1}{a} \qquad && f(x) \textrm{ is vertically stretched by a factor of } \frac{1}{a}
\end{aligned}$$

Be very careful, as horizontal stretching by a factor of $a$ is actually multiplying by a factor of $\frac{1}{a}$.

## Reflection

Multiplying the contents of a function by $-1$ can reflect the function across the $x$ or $y$ axis.

$$\begin{dcases}
		f(x) \rightarrow f(-x) \qquad f(x) \textrm{ is reflected by y-axis } \\
		f(x) \rightarrow -f(x) \qquad f(x) \textrm{ is reflected by x-axis }
\end{dcases}$$

## Modulus

Similar to reflection, adding an absolute value reflects all negative
values across an axis. 

$$\begin{dcases}
		f(x) \rightarrow f(|x|) &  f(-x) = f(x) \\
		f(x) \rightarrow |f(x)| & -f(x) = f(x)
\end{dcases}$$

---
title: Sequence and Series
description: Unit 1 of Math AA HL
---

# Sequence, Series, and Sigma Notation

A sequence is a list of number that is written in a defined order.
A sequence usually follows a predefined list of rules.
The numbers of the sequence are called terms.
Sometimes, the sequence is also referred to as a progression.

$$\begin{aligned}\sum_{n=a}^{b} c\end{aligned}$$

The Sigma Notation is way to write the addition of a sequence.
Sigma notation is written above, $a,b,c$ are the variables.
$a$ represents the starting value of $n$.
$b$ represents the largest value of $n$.
$c$ is the equation that is to be added.

# Arithmetic and Geometric Sequences and Series

## Arithmetic Sequence

An arithmetic sequence is a series of numbers in a linear relationship.
Modeled by the equation: 

$$\begin{aligned}U_n = U_1 + (n-1)d\end{aligned}$$

Where $U_n$ represents the nth term. $U_1$ represents the first term.
And $d$ represents the difference between each term.

The sum of an arithmetic sequence is modeled by this equation:

$$\begin{aligned} S_n &= \frac{n}{2}(u_1+u_n) \\ &= \frac{n}{2}(2u_1+(n-1)d) \end{aligned}$$

This equation averages the first and last term, then multiplies the average by $n$ numbers of terms.

## Geometric Sequences and Series

An geometric sequence is a series of numbers in a exponential relationship.
Modeled by: 

$$\begin{aligned}U_n = U_1 \cdot r^(n-1)\end{aligned}$$

Where $U_n$ is the nth term of the sequence, $U_1$ is the first term is the sequence, and $r$ is the common ratio.
If the common ratio is 1, then the sequence will be a uniformed sequence.
If the common ratio is 0, then all the sequence will start with a value, and continue with all zeros.
If the common ratio is negative, then the sequence will oscillate between negative and positive.

The sum of a geometric sequence can be modeled by, where $n \neq 1$:

$$\begin{aligned} S_n &= \frac{u_1(r^n-1)}{r-1} \\ &= \frac{u_1(1-r^n)}{1-r} \end{aligned}$$

An infinite geometric series is convergent when the sum of the series is a finite value.
If a geometric series is not convergent, it is divergent.
Generally, the common ratio of the geometric sequence have to be less that 1 but larger than 0 in order to be convergent. 
The sum of a infinite convergent geometric sequence can be modeled by:

$$\begin{aligned}S_\infty = \frac{U_1}{1-r}\end{aligned}$$

## Financial Applications

Geometric Sequences is sometimes used to calculate the interest of a deposit or similar circumstances. A equation to model this is:

$$FV = PV \cdot ( 1 + \frac{r}{100k} )^{kn}$$

Where $FV$ is the future value, $PV$ is the present value, $n$ is the number of years, $k$ is the compound periods per year, and $r$ is the nominal annual rate of interest in percent.
If $r$ is negative, then there is exponential decay.

# Proof

A proof is a way to mathematically validate a statement.

**TODO: write down example of proofs**

## Direct Proof

A direct proof is a way of showing the truth of a given statement by constructing a series of reasoned connected established facts.
First, we identify the statement.
Then, we use axioms, theorems, to make deductions that prove the conclusion of your statement to be true.

## Proof by Contradiction

If a logical reasoning is true, than the contrapositive is false.
First, we identify the implication of the statement.
Then assume the implication is false.
Use axioms, theorems, etc to arrive at a contradiction.
This proves that the original statement is true.

## Proof by Induction

First, we find the starting point of a process.
This is called the basic step.
Then, we continue with the basic step until we reach the inductive step.
Finish proof.

# Counting Principles and the Binomial Theorem

## Factorial Notation

The factorial notation ($!$) is a way to denote the multiplication of a certain length of integers.
Factorial notation tends to result in very large numbers.

$$\begin{aligned}n! = n \cdot (n-1) \cdot (n-2) \cdot \cdots \cdot 3 \cdot 2 \cdot 1 \end{aligned}$$

A division of a bigger factorials by a smaller factorial can be down in the following method:

$$\begin{aligned} \frac{5!}{3!} &= \frac{5 \cdot 4 \cdot 3 \cdot 2 \cdot 1}{3 \cdot 2 \cdot 1} \\ &= 5 \cdot 4 \end{aligned}$$

## Permutation

Permutation is written is the format of:

$$\begin{aligned} {}^{n}\!P_{k} = \frac{n!}{(n-k)!} \end{aligned}$$ 

Where $n$ is the objects to chose from and $r$ is the number of objects chosen.
Permutation is used in a situation where order of arrangement matters.
This also means repetition of same sequence in different order is allowed.

## Combinations

Combinations is written in the format:

$$\begin{aligned} {}^{n}C_{r} = \frac{n!}{r!(n-r)!} \end{aligned}$$ 

Where $n$ is the objects to chose from and $r$ is the number of objects chosen.
Combination is used in a situation where order does not matter.
This also means that repetitions of the same sequence is not allowed.

## Binomial Theorem

Binomial Theorem models the resulted equation from $(a+b)^n$.
Where $r$ is the r-th term inside the sequence.

$$\begin{aligned} (a+b)^n = {}^{n}C_{0} a^n b^0 + {}^{n}C_{1} a^{n-1} b^1 + {}^{n}C_{2} a^{n-2} b^2 + \cdots + {}^{n}C_{r} a^{n-r} b^r + \cdots + {}^{n}C_{n} a^0 x^n \end{aligned}$$

Note, the prefix for each term (Combination value) also corresponds to Pascal's Triangle.

|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=0$  | |   |   |   |   |    |    | 1  |    |    |   |   |   |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=1$  | |   |   |   |   |    | 1  |    | 1  |    |   |   |   |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=2$  | |   |   |   |   | 1  |    | 2  |    | 1  |   |   |   |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=3$  | |   |   |   | 1 |    | 3  |    | 3  |    | 1 |   |   |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=4$  | |   |   | 1 |   | 4  |    | 6  |    | 4  |   | 1 |   |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=5$  | |   | 1 |   | 5 |    | 10 |    | 10 |    | 5 |   | 1 |   |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|
|$r=6$  | | 1 |   | 6 |   | 15 |    | 20 |    | 15 |   | 6 |   | 1 |
|-------+-+---+---+---+---+----+----+----+----+----+---+---+---+---|

We can find the specific term from binomial expansion by using this expression:

$$\begin{aligned} {}^{n}C_{r} a^r b^{n-r} \end{aligned}$$

A more generalized Binomial Theorem that supports negative exponents can be found here:
We can use this expression to manually calculate surds.

$$\begin{aligned} (1+x)^a = 1 + ax + \frac{a(a-1)}{2!} + \frac{a(a-1)(a-2)}{3!} + \cdots + \frac{a(a-1)(a-2)\cdots(a-r+1)}{r!} x^r + \cdots \end{aligned}$$

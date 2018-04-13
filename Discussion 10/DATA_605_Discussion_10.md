DATA 605 - Discussion 10
================
Joshua Sturm
04/10/2018

Section 11.1, Page 414, Exercise 8

Exercise 8
==========

A certain calculating machine uses only the digits 0 and 1. It is supposed to transmit one of these digits through several stages. However, at every stage, there is a probability p that the digit that enters this stage will be changed when it leaves and a probability *q* = 1 − *p* that it won’t. Form a Markov chain to represent the process of transmission by taking as states the digits 0 and 1. What is the matrix of transition probabilities?

Solution
========

If we wanted to visualize how the machine works:

*X*<sub>1</sub> → STAGE 1 → *X*<sub>2</sub> → STAGE 2 → *X*<sub>3</sub> → STAGE 3 → *x*<sub>4</sub> → ⋅ ⋅ ⋅

At each stage (or step), *X*<sub>*i*</sub> can take on one of two values (or states): *S* = {0, 1}.

The transition matrix will be

$$
P = 
\\begin{pmatrix}  
q & p \\\\
p & q
\\end{pmatrix}
= 
\\begin{pmatrix}
1 - p & p \\\\
p & 1 - p
\\end{pmatrix}
$$

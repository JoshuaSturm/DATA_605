DATA\_605\_Discussion\_13
================
Joshua Sturm
May 3, 2018

Section 4.1, Page 163, Exercise \#7

Use 5 iterations of Newton’s Method with the given initial approximation to approximate the root. Compare it to the known value of the root.

*f*(*x*)=ln(*x*),   *x*<sub>0</sub> = 2

Formula for Newton's Method:

$$
x\_{n+1} = x\_n - \\frac{f(x\_n)}{f'(x\_n)}
$$

![](DATA_605_Discussion_13_files/figure-markdown_github/graph-1.png)

$$ 
\\dfrac{\\mathrm{d}}{\\mathrm{d}x}  = \\frac{1}{x}
$$

| Iteration | Newton Approximation | Actual Value | Difference |
|:---------:|:--------------------:|:------------:|:----------:|
|     1     |       0.6137056      |       1      |  0.3862944 |
|     2     |       0.9133412      |       1      |  0.0866588 |
|     3     |       0.9961317      |       1      |  0.0038683 |
|     4     |       0.9999925      |       1      |  0.0000075 |
|     5     |       1.0000000      |       1      |  0.0000000 |

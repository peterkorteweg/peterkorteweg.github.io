+++
title = 'Young Gauss'
draft = false
type = 'page'

+++

**Question:** In the late 18th century, somewhere in an elementary school in Germany, a teacher gave his students the task of adding all the numbers from 1 to 100. He expected to have some rest, but within 10 seconds the young mathematician [Carl Gauss](https://en.wikipedia.org/wiki/Carl_Friedrich_Gauss) gave the correct answer. How did he do that?

[**Answer**](/puzzles/gauss_answer/):  Rewrite the sum $1+ 2 + ... + 99 + 100 = (1+100) + (2+99) + ...= \frac{100}{2}101=5050$ .

In general, $\sum_{i=1}^{n}{i}=(n+1)n/2$. We can prove this using induction. Suppose the statement is true for all $n\leq N-1$. We now apply induction to prove that the statement is also true for $N$. 

$\sum_{i=1}^{N}{i}=\sum_{i=1}^{N-1}{i}+N=N(N-1)/2+N=[N(N -1)+2N]/2=(N+1)N/2$.




+++
title = 'The hiring problem'
draft = false
type = 'page'

+++

**Question:** Your team wants to hire a new colleague. The team wants to interview at most $K$ persons, and candidates are interviewed one at a time. After each interview the team has to decide to hire or reject the candidate. How can your team maximize the probability of hiring the best candidate amongst $K$ persons?

[**Answer**](/puzzles/hiring_problem/): first interview $R$ candidates and reject all. Then interview candidates until you find a candidate that is better than all of the first $R$ candidates. The number $R$ depends on the maximum number $K$ that you wish to interview.

For $K=5$, $R=2$

For $K=10$, $R=3$

For $K=100$, $R \approx \frac{K}{e}-1 \approx 36$.

This puzzle is known as the [Secretary Problem](https://en.wikipedia.org/wiki/Secretary_problem); see the link for the exact formula to calculate $R$. 

The solution also shows the disadvantage of interviewing candidates one at a time: the first $R$ candidates interviewed never have a chance to be hired as they become the benchmark to beat!

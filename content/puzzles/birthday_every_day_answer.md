+++

title = "Every day is someone's birthday"
draft = false
type = 'page'

+++

![New Yorker, Amy Hwang](/images/NewYorker_AmyHwang_Birthday.jpg) 

[Copyright: Amy Hwang](https://condenaststore.com/featured/everyday-is-someones-birthday-amy-hwang.html)

**Question:** "When you work at a multi-billion dollar company, it's someone's birthday every day." How many employees do you need to have, in expectation, a birthday every day?

You may assume a year consists of 365 days, and each day has equal probability of being someone's birthday.

[**Answer**](/puzzles/birthday_every_day/): 2365.

Let $F$ be the expected number of employees needed. Let $f_t$ be the number of additional employees needed to have exactly $t$ different birthdays, assuming the group of employees sofar cover $t-1$ birthdays. The probability that an additional employee has a new birthday is $p_t=\frac{365-(t-1)}{365}$. E.g. $p_1 = \frac{365}{365}=1$, $p_2 = \frac{364}{365}$, $\ldots$, $p_{365} = \frac{1}{365}$. In expectation one needs $E[f_t]=1/p_t$ additional employees.  By the linearity of expectations, one thus needs in expectation: $E[F] = \sum_{t=1}^{365}\frac{1}{p_t}=\frac{365}{365} + \frac{365}{364} + \ldots + \frac{365}{1} = 365 (\frac{1}{1} + \frac{1}{2} + \ldots + \frac{1}{365}) = 365 \cdot H_{365}$, where $H_n$ is the harmonic number.

The exact number $365 \cdot H_{365} = 2364.7$ ; using the approximation of the Harmonic number $H_n \approx ln(n) + 0.58n + 1/2 = 2365.15$.

This problem is known as the [Coupon Collector's problem](https://en.wikipedia.org/wiki/Coupon_collector%27s_problem). The average number of persons needed, exceeds the median number of persons needed, which is 2287; see [Flowing Data](https://flowingdata.com/2017/06/05/how-many-friends-you-need-to-have-a-birthday-every-day-of-the-year/) for the simulation.


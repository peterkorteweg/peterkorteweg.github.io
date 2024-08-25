+++
title = 'Two envelopes'
draft = false
type = 'page'

+++

**Question:** A quizmaster shows you two envelopes. He tells you that each envelope contains a sum of money, and the amount in one of the envelopes is twice the amount of the other envelope. You choose an envelope, and when you open it you see it contains €1000, in €100 notes. The quizmaster says that if you give him a €100 note, you may switch envelopes. Do you choose to switch?

[**Answer**](/puzzles/two_envelopes/): you do not switch, because that maximizes your expected payout. Let the amounts in the envelopes be $M$ en $2M$. Then, the expected value of each envelope is $E[e1]=E[e2]=3M/2$. If you choose to switch your expected payout will be lowered to  $3M/2-100$.

A common mistake is to misinterpret the information that you get when opening the first envelope. The reasoning is: the first envelope contains 1000 euro, so the other envelope must contain either 500 euro or 2000 euro (correct). "Hence", the expected value of the other envelope is $\frac{1}{2} \ast 500+ \frac{1}{2} \ast 2000=1250$ (incorrect). The second statement is not correct because one cannot determine the probabilities. A simple way to see that the second statement cannot be correct, is that this statement would **always** result in switching, regardless of the first envelope chosen. In contrast to the [Monty Hall problem](https://en.wikipedia.org/wiki/Monty_Hall_problem), the information in the envelope does not help us(!).

This problem is known as the [Exchange paradox](https://en.wikipedia.org/wiki/Two_envelopes_problem).


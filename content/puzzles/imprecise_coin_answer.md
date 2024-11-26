+++
title = 'An imprecise coin'
draft = false
type = 'page'

+++

**Question:** You would like to choose between two holiday destinations by flipping a coin. However, the only coin you have is not a perfect coin. How can you still use this coin to make a fair choice? How many coin flips does your solution require on average?

[**Answer**](/puzzles/imprecise_coin/): A single coin flip results in heads (H) or tails (T) with unknown probability. But for two consecutive coin flips the probability of HT equals the probability of TH. Use the coin as follows: flip the coin twice: if the outcome is HT, choose the first destination, and if the outcome is TH choose the second destination. If the outcome is HH or TT, repeat the above.

While this solution works, there is a potential problem. The probability of the outcomes HT or TH is $2 p_k p_m \equiv p < 1/2$.  The expected number of coin flips is then $\sum_{n=1}^{\infty} [(2i)(1-p)^{i-1}p]=2/p$. The average number of flips is potentially unbounded if $p \rightarrow 0$.

Source: [Haigh](/puzzles/#literature).

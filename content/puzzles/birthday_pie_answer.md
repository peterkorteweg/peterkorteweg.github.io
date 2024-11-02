+++

title = 'The birthday pie'
draft = false
type = 'page'

+++

**Question:** A birthday pie is divided among 8 guests, as follows. The first guest gets $1/8$th of the pie, the second guest $2/8$th of the remaining pie, etc. Who gets the biggest piece? 

Can you solve it as well for 100 guests, where the $k$-th guest receives $k/100$ of the remaining pie?

[**Answer**](/puzzles/birthday_pie/): The third guest gets the biggest piece. The shares received are:

1/8, 7/32, **63/256**, 105/512, and smaller fractions for the later guests. 63/256 $\approx$ 25%, the largest piece of the pie.

In general the puzzle can formulated as follows. There are $N$ guests, and the $k$-th guest receives $k/N$ of the remaining pie. Now, let $x$ be the remaining fraction of the pie when the $k$-th guest is being served. The $k$-th guest thus receives $x \cdot \frac{k}{N}$, after which there is $x \cdot \frac{N-k}{N}$ left for guest $k+1$. Therefore the $k+1$-th guest receives  $[x \cdot \frac{N-k}{N}] \cdot \frac{k+1}{N}$. Guest $k+1$ receives a larger fraction then guest $k$ if  $[x \cdot \frac{N-k}{N}] \cdot \frac{k+1}{N} > x \cdot \frac{k}{N}$ which rearranges to

$-k^2 -k + N > 0$

For N=100 this is true for $k < 10$, which means the 10th guest receives the largest piece of the pie.

Source: [Pythagoras Magazine](https://www.pyth.eu/) 


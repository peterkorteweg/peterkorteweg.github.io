+++

title = 'No birthday'
draft = false
type = 'page'

+++

**Question:** 

1. You have twelve friends. What is the probability none of them has their birthday in January?
2. You have 365 friends in your social network. What is the probability that none of them have their birthday on 1 January?

[**Answers**](/puzzles/birthday_no/): 

1. 35%. Each friend has their birthday in one of the other 11 months, i.e. assuming uniformly distributed birthday amongst 12 months $(\frac{11}{12})^{12} \approx 0.352$ or uniformly distributed birthdays amongst 365 days $(\frac{365-31}{365})^{12} \approx 0.348$.
2. 36.7%. Each friend has their birthday on one of the other 364 days,  $(\frac{364}{365})^{12} \approx 0.367$.

The answers are almost similar because both are part of the sequence $(\frac{n-1}{n})^n$ which converges to $1/e \approx 0.368$; see [List of representations of *e*](https://en.wikipedia.org/wiki/List_of_representations_of_e).
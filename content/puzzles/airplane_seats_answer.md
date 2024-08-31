+++

title = 'Airplane seats'
draft = false
type = 'page'

+++

**Question:** An airplane with 100 seats is fully booked. Passengers enter the airplane one at a time. The first passenger cannot find their ticket, and chooses a random seat. Each next passenger sits on their own seat, or in case their seat is taken, chooses an available seat at random. What is the probability that the last passenger finds their own seat available?

[**Answer**](/puzzles/airplane_seats/) $1/2$. 

Consider the first passenger that find their seat taken by another passenger. This means either of these two passengers needs to look for another seat. To answer the question, it does not matter which of the two passengers needs to choose another seat. Let us assume that each time a passenger finds their seat taken, the *seated passenger* needs to find another seat at random. As a consequence this means that the first passenger keeps choosing new seats until they find either their own seat, or they choose the seat of the last passenger. I.e., one can ignore all other passengers. Regardless of the total number of passengers, the probability that the first passenger at the end chooses their own chair is $\frac{1}{2}$, hence the probability of the last passenger finding their own seat available is also $\frac{1}{2}$.

Source: [Bogomolny](/puzzles/#literature).

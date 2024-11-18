+++
title = 'The mountain hiker'
draft = false
type = 'page'

+++

**Question:** A mountain hiker leaves early in the morning from her hotel in the valley. She climbs all day and reaches a mountain lodge at the foot of the summit in the evening, and stays there for the night. The next day she continues to climb, reaches the summit and descends back to the hotel where she arrives in the evening. Is it possible that the hiker was at the same altitude at the same time on both the first and second day?

[**Answer**](/puzzles/mountain_hiker/): Yes. In fact, this is always true, no matter how fast the speed of the hiker on the way up and down. Imagine two hikers walking on the same day: hiker 1 hikes the route of day 1, and hiker 2 hikes the route of day 2. In the morning, hiker 1 is at a lower altitude than hiker 2, and at a higher altitude in the evening. So at some point during the day the hikers are at the same altitude. This must be at the same time.

This is an illustration of the [intermediate value theorem](https://en.wikipedia.org/wiki/Intermediate_value_theorem), which states that a real function $f$ in an interval $[a,b]$ takes all possible values between $f(a)$ and $f(b)$. Let $h_1(t)$ be the hiker's altitude on day 1, and $h_2(t)$ be the altitude on day 2, and the day consists of interval $[0,T]$. Then we know $h_1(0)<h_2(0)$ and $h_1(T)>h_2(T)$. We now choose $h(t)=h_1(t)-h_2(t)$, so $h(0)<0$ and $h(T)>0$, so there must be a moment in the day $h( t)=0$.

Source: [Pentagram](/puzzles/#literature).

### Discrete Uniform Distribution

Right now we are talking specifically about **discrete** probabilities, but I would like to introduce you to a type of distribution.  A good example of this is rolling a dice.  Every outcome has the same probability & therefore we call if uniform.  The discrete values that the dice throw can take on are _1,2,3,4,5,6_ with each having the same probability of showing.  Assuming that the dice is **fair** each of these probabilities are 1/6.

We can also look at the **mean** and the **variance** of such distribution.  This gives a good intuition of what to expect when rolling the dice.  **In general we call this (the mean) the expectation value** and we will get into that more later on.  For now, lets just look at how to calculate the **mean** and **variance**.


To calculate the mean, we use the following equation:


```latex
Mean[dice] \space = \space E[dice] = 1×P(dice = 1) + 2×P(dice = 2) + 3×P(dice = 3) + 4×P(dice = 4) + 5×P(dice =5 ) + 6×P(dice = 6)
````

We can go ahead and rewrite this equation with the following:

- X represents the die
- E[X] represents the expectation or mean of all the rolls

```latex
E[X] = 1×P(X = 1) + 2×P(X = 2) + 3×P(X = 3) + 4×P(X=4) + 5×P(X=5) + 6×P(X=6)
````

We can then Generalize this to:
- f(x) is the value of the dice
- P(X = x) is probability of rolling that value
```latex
E[ f(X) ] = f(x) \space P(X = x)
```

When we apply this formula, for the **fair** dice, we get the following:
```latex
1*(1/6) + 2*(1/6) + 3*(1/6) + 4*(1/6) + 5*(1/6) + 6*(1/6) = 3

```
This makes sense, because if roll a dice multiple times, we will find that the average of all the rolls will trend towards the value of 3!  Try it out (with more than 20 rolls)


In the next card, we will explore how to calculate the variance of a dice

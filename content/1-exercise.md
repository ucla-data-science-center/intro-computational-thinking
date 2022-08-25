---
title: Exercise 1
nav: Exercise
---

Some people are very good at adding numbers up in their heads while others struggle.  

In this exercise, we will examine how to add up all the numbers between 1 and 200 within a minute.

Computational thinking can help. Using the first step - *Decomposition* - we can break the problem up into smaller pieces.

*Decomposition*

We begin by adding the first and last numbers.

What is 200 + 1?

The answer is **201**.

Then we add up the second and the second last numbers, i.e. 199 + 2.

The answer is **201**.

Then we add up the third and the third last numbers, i.e. 198 + 3.

The answer is **201**.

-------

Using our second step - *Pattern Matching* - we may now be able to spot a pattern, i.e. that each pair of numbers will add up to **201**.

If we are adding all the numbers between 1 and 200, we will end up with 100 pairs, all of which add up to **201**.

-------

Using an *Algorithm* - a step - how do we calculate the final total?

We multiply 100 (the number of pairs) by the total to which each pair adds up (**201**).

100 * 201 -> gives us an answer of **20,1000**.

-------

But what about about our fourth step, *Abstraction*. 

*Abstraction* will enable us to repeat the process we used to add 1-200 to add up a different set of numbers, e.g., 1-500.

The *Algorithm* will be 

(`number to be added` divided by 2) multiplied by (`number to be added` +1). We can express that as an algebraic formula:

`(*x*/2) * (*x* + 1)`

where *x* is the `number to be added.`

-------------

#### Practice

Use the algorithm above to add up all the numbers betwen 1 and 400, 1 and 2000, and 1 and 20,000.
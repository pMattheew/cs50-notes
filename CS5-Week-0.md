# CS50 Week 0 - Scratch

Problem solving start with an **input** and ends with an **output**, so what happens between both is what the developer had to create to solve the given problem.

An example problem could be:
- To take attendance in the beggining of the class

#### Unary
We could use a _system_ called **unary** to count every student in the class - we can compare it as a fancy way of counting like 1, 2, 3, 4, 5...
With it we can use a single symbol to solve a problem, like counting the number of people in the room. It can also be called **base-1**, and might be not used very often.

#### Binary
Computers most often use the **binary** system, that can just have one or another value, _true_ or _false_. It's name origin is from _binary digit_, we could have an analogy for it's origin after removing some letters of it like this:
```
binary digit
bi         t
bit
```
It's also know as **base-2**.

---

Both systems relate to one that we are already very used to that is the **base-10** system, a.k.a. **decimal**. If we rewind to our primary school and see how decimals work we can also see that's very similar that we do with unary and binary:

Lets consider the number 123: 

```
   Decimal

    10²      10¹     10⁰  # They could be represented by powers
    100       10       1  # These are the places: hundreds, tens and units respectively
      1        2       3
100 x 1 + 10 x 2 + 1 x 3  =  123

--------------------------------
   Binary
   
...  2²   2¹   2⁰  # And so forth...
      4    2    1
      1    1    1
      4 +  2 +  1  = 7
```
With this example it is possible to see that it's more easier to count in computer's way using binaries than decimals.

---

A bit alone is not such useful so the most used unit to represent them is the **byte**, that is a combination of eight bits, and it can hold a maximum number of 255.

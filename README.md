## Task Description ##

Implement method [Calculate(a, r, n)](ArithmeticSequenceTask/ArithmeticSequence.cs#L7) that calculates the sum of the first `n` elements of a sequence in which each element is the sum of the given integer `a`, and a number of occurrences of the given integer `r`, based on the element's position within the sequence.

> For example: 
```
Calculate(2, 3, 5) -> 40
```
```
1     2        3          4            5
a + (a+r) + (a+r+r) + (a+r+r+r) + (a+r+r+r+r) 
2 + (2+3) + (2+3+3) + (2+3+3+3) + (2+3+3+3+3) = 40
```

*Topics - basic operation, loops.*
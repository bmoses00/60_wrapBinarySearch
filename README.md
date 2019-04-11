# 60_wrapBinarySearch

---
Explanation of Logarithm:
---

y = log x (base two) relates two variables, x and y.

Essentially, 'y' is the exponent of 2 that
makes Math.pow(2, y) equal to 'x'.

Its graph looks similar to a square root curve,   
except flatter.

---
 Recursive problem:
---

 0. problem:
 In a list of size n, find the index of a desired element.

 1. recursive abstraction:
 When I am asked to find the index of a desired element in a
 list of size n, the recursive abstraction can find the index
 of the desired element in a list of size approximately n/2

 2. Binary decision:
 (1) Is the size of the list one or lower
 OR
 (2) Has the desired element been found

 Solution to the base cases:   
 (1) Return -1   
 (2) Return the index of the desired element   

 Solution the recursive cases:  

 (no leftover processing)   
 (no concatenation)   

 (1) If the index of the desired element is lower than   
 the index currently being checked*,   
 then follow these instructions for the list of index 0   
 to index currently being checked - 1   
 (2) Else,  
 follow these instructions for the list of index currently   
 being checked* + 1 to the last element of the list    

*index currently being checked is the middle index

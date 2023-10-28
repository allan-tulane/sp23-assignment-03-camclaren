# CMPS 2200 Assignment 3
## Answers

**Name:** Cameron McLaren


Place all written answers from `assignment-03.md` here for easier grading.


- **b.**

W(n) = O(n)
S(n) = O(n)


- **d.**

map: W(n) = O(n), S(n) = O(1)
scan: W(n) = O(n), S(n) = O(lgn)
reduce: W(n) = O(n), S(n) = O(lgn)


- **f.**

W(n) = 2W(n/2) + 1
leaf dominated
 num leaves: 2^lgn

therefore: O(n)

S(n) = S(n/2) + 1
balanced

therefore: O(lgn)
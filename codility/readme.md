# Codility Problems

## 1. Time Complexity
### 1.1 Recap on Complexity Theory
1. How well our code will scale with data.: O(n)

### 1.2 Equilibrium Problem
1. Write a fn that takes an array as input and returns abs diff, where abs diff between left and right (split at P) in at a minimum.
2. limits of fn: array: [3,1,2,4,3]
    * n ---> 0 - 200000
3. Sol 1: O(n * n): 
    - traverse left to right

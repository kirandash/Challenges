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
4. **Solution Steps**:
    * Initial left sum, right sum, diff
    * loop once through array
    * add one item to left sum and subtract from right sum. and if new diff is less than prev: update diff
    * return diff

### 1.3 Arrays - Cyclic Rotation
1. arrays are static structures.
    * allocate memory once and not resize it.
    * some languages allows us to resize array but will const performance penalty
2. Problem: Cyclic Rotation: 
    * [7,2,8,3,5] - clockwise rotation
3. Write a fn: solution(a,k) that returns an array with content rotated by k times to the right
4. Ex: Input: solution([5,3,4,1,2], 2) ---> [1,2,5,3,4]
5. Hint: The ramainder trick
    * the remainder can never be more than the divisor
6. **Solution steps**:
    * create result array with 5 empty items
    * loop through input array
    * Formular: `(i + k) % size`: i: index, k: positions to rotate, size: array length
    * move item from input array to result arrays new index calculated based on the above formula.
7. Real time application:
    - Circular buffers
    - Hashed rotation

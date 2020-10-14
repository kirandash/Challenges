# Sample Test

## 1. Reverse a String
1. without built in fn: 
    * `mystr.reverse('').split().join('')`
    * `for loop through string in reverse` and use `mystr.charAt(i)` to append to result

## 2. Length of nested array

## 3. Given a positive integer num, write a function which returns True if num is a perfect square else False. 
1. Note: Do not use any built-in library function such as sqrt. 
    * Example 1: Input: 16 Returns: True
2. Sol:
    * check if num is positive (num) > 0) and check if sqrt is integer ( Math.sqrt(num) % 1 === 0 )
    * Use BST

## 4. Given a set of non-overlapping intervals, insert a new interval into the intervals (merge if necessary). 
1. You may assume that the intervals were initially sorted according to their start times. 
    * Example 1: Given intervals [1,3],[6,9], insert and merge [2,5] in as [1,5],[6,9]. 
    * Example 2: Given [1,2],[3,5],[6,7],[8,10],[12,16], insert and merge [4,9] in as [1,2],[3,10],[12,16]. This is because the new interval [4,9] overlaps with [3,5],[6,7],[8,10].

## 5. Word search: Given a 2D board and a word, find if the word exists in the grid. (Must be continuous path - horizontal or vertical)
1. For example, Given board = 
[ 
  ['A','B','C','E'], 
  ['S','F','C','S'], 
  ['A','D','E','E'] 
] 
word = 'ABCCED', -> returns true, 
word = 'SEE', -> returns true, 
word = 'ABCB', -> returns false.

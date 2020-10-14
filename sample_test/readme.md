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

# Interview Questions 101
### Some Interview Questions for Everyone to practice


```
Q1. You are given a 2 D matrix with only 0 and 1. 
You need to find out the row with maximum number of 1s.
Note: The matrix is row wise sorted.
Example:

Input
0 1 1 1
0 0 1 1
1 1 1 1 
0 0 0 0

Output: 2

```
[Question Link](https://www.geeksforgeeks.org/find-the-row-with-maximum-number-1s/)



```
Q2. Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

An input string is valid if:

1) Open brackets must be closed by the same type of brackets.
2) Open brackets must be closed in the correct order.


Input: s = "()[]{}"
Output: true

Input: s = "([)]"
Output: false
```

[Quesstion Link](https://leetcode.com/problems/valid-parentheses/)



### Design Question
```
Q3 Sorted-Order Data Structure (gongjinc@)
Imagine you have a stream of number coming from some system and you want to store them. Design a data structure to store the these numbers. Given a number in the structure, tell the ranking of the number in the natural order of the value.

Example: for a list of numbers 1, 2, 6, 5, 7, when given the number 5, return 3 as 5 ranks the 3rd smallest number.

Solutions
ArrayList: O(n) insert, O(log(n)) lookup with binary search
Binary search tree: O(log(n)) insert, O(log(n)) lookup. Optimal
LinkedList+Dictionary: Lookup will be O(1), Insert will be O(nlog(n))
```

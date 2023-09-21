### 1. Two Sum

- **Description:** Given an array of integers, find two numbers such that they add up to a specific target.
- **Input:** Array of integers: `[2, 7, 11, 15]`, Target sum: `9`
- **Expected Output:** Indices of the two numbers that add up to the target: `[0, 1]` (because `2 + 7 = 9`)

### 2. Reverse a String

- **Description:** Implement a function to reverse a string in-place.
- **Input:** String to reverse: `"hello"`
- **Expected Output:** Reversed string: `"olleh"`

### 3. Palindrome Check

- **Description:** Determine whether a given string is a palindrome (ignoring spaces, punctuation, and capitalization).
- **Input:** String to check: `"A man, a plan, a canal, Panama"`
- **Expected Output:** Is a palindrome: `True`

### 4. FizzBuzz

- **Description:** Print numbers from 1 to n, but replace multiples of 3 with "Fizz" and multiples of 5 with "Buzz."
- **Input:** `n = 15`
- **Expected Output:** `["1", "2", "Fizz", "4", "Buzz", "Fizz", "7", "8", "Fizz", "Buzz", "11", "Fizz", "13", "14", "FizzBuzz"]`

### 5. Longest Substring Without Repeating Characters

- **Description:** Find the length of the longest substring without repeating characters in a given string.
- **Input:** String: `"abcabcbb"`
- **Expected Output:** Length of the longest substring without repeating characters: `3` (e.g., `"abc"`)

### 6. Merge Intervals

- **Description:** Given a collection of intervals, merge any overlapping intervals.
- **Input:** List of intervals: `[[1,3],[2,6],[8,10],[15,18]]`
- **Expected Output:** Merged intervals: `[[1,6],[8,10],[15,18]]`

### 7. Implement a Stack

- **Description:** Implement a stack data structure with push, pop, top, and getMin operations, all in constant time.
- **Input:** Operations: `["push(1)","push(2)","top()","pop()","getMin()"]`
- **Expected Output:** `2` (after the operations, top should return 2, and getMin should return 1)

### 8. Binary Tree Level Order Traversal

- **Description:** Given a binary tree, return its level order traversal as a list of lists.
- **Input:** Binary Tree:
3
/
9 20
/
15 7

- **Expected Output:** Level order traversal: `[[3],[9,20],[15,7]]`

### 9. Maximum Subarray

- **Description:** Find the contiguous subarray within an array that has the largest sum.
- **Input:** Array of integers: `[-2,1,-3,4,-1,2,1,-5,4]`
- **Expected Output:** Maximum sum of a contiguous subarray: `6` (the subarray `[4,-1,2,1]` has the largest sum)

### 10. LRU Cache

- **Description:** Implement an LRU (Least Recently Used) cache with constant time operations for get and put.
- **Input:** Operations: `["LRUCache","put(1,1)","put(2,2)","get(1)","put(3,3)","get(2)","put(4,4)","get(1)","get(3)","get(4)"]`
- **Expected Output:** `[null,null,null,1,null,2,null,1,3,4]`

### 11. Word Search

- **Description:** Given a 2D board and a word, check if the word exists in the board.
- **Input:** 2D board and word to search: 
board = [
['A','B','C','E'],
['S','F','C','S'],
['A','D','E','E']
]
word = "ABCCED"

- **Expected Output:** Does the word exist in the board: `True`

### 12. Median of Two Sorted Arrays

- **Description:** Given two sorted arrays, find the median element.
- **Input:** Sorted Arrays: `[1, 3]` and `[2]`
- **Expected Output:** Median: `2.0` (The median of the merged array `[1,2,3]` is 2.0)

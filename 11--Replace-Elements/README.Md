# Replace Elements with Greatest Element on Right Side

Given an array `array`, replace every element in that array with the greatest element among the elements to its right, and replace the last element with `-1`.

Example 1:

```
Input: array = [17,18,5,4,6,1]
Output: [18,6,6,6,1,-1]
Explanation:
- index 0 --> the greatest element to the right of index 0 is index 1 (18).
- index 1 --> the greatest element to the right of index 1 is index 4 (6).
- index 2 --> the greatest element to the right of index 2 is index 4 (6).
- index 3 --> the greatest element to the right of index 3 is index 4 (6).
- index 4 --> the greatest element to the right of index 4 is index 5 (1).
- index 5 --> there are no elements to the right of index 5, so we put -1.
```

Example 2:

```
Input: array = [400]
Output: [-1]
Explanation: There are no elements to the right of index 0.
```

&copy; [LeetCode](https://leetcode.com/explore/learn/card/fun-with-arrays/511/in-place-operations/3259/)

Happy Coding :))

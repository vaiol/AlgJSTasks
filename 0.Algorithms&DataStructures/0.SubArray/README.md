## Find sub array with required sum

Given array of positive numbers and positive number S.
Find subarray with required sum >= S. It must be sub array with minimal length .
If there isn't one return 0 instead.

Example 1: 
```
Input: s = 8, arr = [2,3,3,1,4,4]
Output: [4,4]
Explanation: the subarray [4,4] has the minimal length and sum >= S.
Answer [2,3,3] - is incorrect.
```

Example 2: 
```
Input: s = 9, arr = [3,3,3,5,5,1,4,5]
Output: [5,5] or [4,5]
Answer [3,3,3] - is incorrect.
```

# 1. Two Sum
Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

[LeetCode Two Sum Problem](https://leetcode.com/problems/two-sum/description/)


# Solution

To solve the `twoSum` problem with a time complexity better than \(O(n^2)\), we can use a hash map to 
store elements as we iterate through the array. This way, for each element \(x\), we can check if \(target — x\) 
is already in the hash map. If it is, we've found the two numbers that add up to the target and can 
return their indices. This approach has a time complexity of \(O(n)\) because each lookup in the hash 
map takes \(O(1)\) time, and we're doing one pass through the array.

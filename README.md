# Leetcode 1493. Longest Subarray of 1's After Deleting One Element

# Problem

Given a binary array nums, you should delete one element from it.

Return the size of the longest non-empty subarray containing only 1's in the resulting array. Return 0 if there is no such subarray.

# Solution - O(N)

iterate through the list, converting it from 1's and 0's, instead adding 1's together into a single spot. After that, you can iterate through the new list, checking the sum of the values adjacent to each index, returning the max.

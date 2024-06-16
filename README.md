# Merge Sorted Array

LeetCode Q # 88.

You are given two integer arrays nums1 and nums2, sorted in non-decreasing order, and two integers m and n, representing the number of elements in nums1 and nums2 respectively.
Merge nums1 and nums2 into a single array sorted in non-decreasing order.
The final sorted array should not be returned by the function, but instead be stored inside the array nums1. To accommodate this, nums1 has a length of m + n, where the first m elements denote the elements that should be merged, and the last n elements are set to 0 and should be ignored. nums2 has a length of n.

Example 1:

Input: nums1 = [1,2,3,0,0,0], m = 3, nums2 = [2,5,6], n = 3</br>
Output: [1,2,2,3,5,6]</br>
Explanation: The arrays we are merging are [1,2,3] and [2,5,6].
The result of the merge is [1,2,2,3,5,6] with the underlined elements coming from nums1.

Example 2:

Input: nums1 = [1], m = 1, nums2 = [], n = 0</br>
Output: [1]</br>
Explanation: The arrays we are merging are [1] and [].
The result of the merge is [1].

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Merge-Sorted-Array-LeetCode/assets/171427226/7814693d-ab35-4d25-a42f-6afbdaaf8aca)

  Time complexity: O(nlogn).</br>Space complexity: O(1).
</div>

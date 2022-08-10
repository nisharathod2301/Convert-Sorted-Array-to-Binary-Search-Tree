# Convert-Sorted-Array-to-Binary-Search-Tree
Given an integer array nums where the elements are sorted in ascending order, convert it to a height-balanced binary search tree.A height-balanced binary tree is a binary tree in which the depth of the two subtrees of every node never differs by more than one.

https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/

![image](https://user-images.githubusercontent.com/109743699/183845050-90d01b70-e3aa-409c-884e-83717da6d538.png)

Input: nums = [-10,-3,0,5,9]

Output: [0,-3,9,-10,null,5]

Explanation: [0,-10,5,null,-3,null,9] is also accepted:

![image](https://user-images.githubusercontent.com/109743699/183845206-6c5d0f1a-2374-4249-b259-29bedd4189cf.png)

Constraints:

1 <= nums.length <= 104,
-104 <= nums[i] <= 104,
nums is sorted in a strictly increasing order.

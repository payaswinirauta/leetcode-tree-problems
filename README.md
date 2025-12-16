## Binary Tree Maximum Path Sum – LeetCode 124

🔗 [Problem Link](https://leetcode.com/problems/binary-tree-maximum-path-sum/)

Solved using DFS with global maximum tracking.

Key idea:
- For each node, compute max path going up
- Update global max using left + node + right

Complexity:
- Time: O(n)
- Space: O(h)

Status: Accepted

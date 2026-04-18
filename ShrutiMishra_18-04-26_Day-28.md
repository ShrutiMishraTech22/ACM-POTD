PROBLEM: 572. Subtree of Another Tree

APPROACH:
Traverse the main tree and treat each node as a potential starting point of the subtree.
At every node, check whether the subtree rooted there is identical to the given subRoot using a helper function.
The helper function compares both trees recursively by checking node values and their left and right subtrees.
If a match is found at any node, return true; otherwise, continue searching in the left and right subtrees.

Time complexity: O(m x n)

SCREENSHOT:
<img width="1906" height="868" alt="image" src="https://github.com/user-attachments/assets/78132a05-dbe0-4a55-96a0-0d90e1628fcb" />

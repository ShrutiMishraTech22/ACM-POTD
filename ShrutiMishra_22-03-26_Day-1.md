PROBLEM: 3Sum

APPROACH:
I used the sorting and two-pointer technique to solve this problem efficiently.
First, I sorted the array so that I can apply the two-pointer approach and also easily skip duplicates.
For each fixed element, I used two pointers:
- One starting from the next index (left)
- One from the end of the array (right)

Calculated the sum of the three elements:
- If the sum is 0, added the triplet to the result and moved both pointers while skipping duplicates.
- If the sum is less than 0, moved the left pointer forward.
- If the sum is greater than 0, moved the right pointer backward.

Time Complexity:
O(n²)

SCREENSHOT:
<img width="1911" height="858" alt="image" src="https://github.com/user-attachments/assets/7561f946-8e6c-4548-bae9-4a7df4340317" />



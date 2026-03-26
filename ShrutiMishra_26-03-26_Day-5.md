PROBLEM: 3Sum

APPROACH:
I used the sorting and two-pointer technique to solve this problem efficiently. First, I sorted the array so that I can apply the two-pointer approach and also easily skip duplicates. 
For each fixed element, I used two pointers: - One starting from the next index (left) - One from the end of the array (right) 
Calculated the sum of the three elements: - If the sum is 0, added the triplet to the result and moved both pointers while skipping duplicates. 
- If the sum is less than 0, moved the left pointer forward.
- If the sum is greater than 0, moved the right pointer backward.
  
Time Complexity: O(n²)

SCREENSHOT:
<img width="1895" height="844" alt="Screenshot 2026-03-26 232444" src="https://github.com/user-attachments/assets/3dbbc20e-0983-4be6-a995-86aa252a0b26" />

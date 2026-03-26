PROBLEM: 2Sum

APPROACH:
I used the sorting and two-pointer technique to solve the problem efficiently.
First, I sorted the array so that I can apply the two-pointer approach.

Then, I initialized:
One pointer at the start (left)
One pointer at the end (right)

At each step:
Calculate the sum of nums[left] + nums[right]
If the sum equals the target → return the pair
If the sum is less than the target → move the left pointer forward
If the sum is greater than the target → move the right pointer backward

Time Complexity:
O(n log n)

SCREENSHOT:
<img width="1911" height="858" alt="image" src="https://github.com/user-attachments/assets/7561f946-8e6c-4548-bae9-4a7df4340317" />



PROBLEM: 206. Reverse Linked List

APPROACH:
Use iteration with 3 pointers:
  prev → stores previous node
  curr → current node
  next → next node
Reverse links one by one:
  curr.next = prev
Move all pointers forward until list ends

Time Complexity: O(n)

SCREENSHOT:
<img width="1919" height="867" alt="image" src="https://github.com/user-attachments/assets/3206c2f0-b62f-4233-a622-55496e08d063" />

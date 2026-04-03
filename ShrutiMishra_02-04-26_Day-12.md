PROBELM: 83. Remove Duplicates from Sorted List

APPROACH:
Since the list is sorted, duplicates will always be adjacent.
Traverse the linked list using a pointer (curr).
At each node:
If curr.val == curr.next.val → skip duplicate
curr.next = curr.next.next
Else → move forward (curr = curr.next)
Continue until end of list.

Time Complexity: O(n)

SCREENSHOT:
<img width="1918" height="869" alt="image" src="https://github.com/user-attachments/assets/4f1e464e-af51-497b-b442-d8e178018d78" />

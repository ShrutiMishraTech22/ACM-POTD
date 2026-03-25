PROBLEM: 268 Missing Number

APPROACH: 
Used XOR properties: a ^ a = 0 and a ^ 0 = a
Initialize xor with array length and loop from 0 to n-1
At each step: xor = xor ^ i ^ nums[i]
All matching numbers cancel out and the remaining value in xor is the missing number

SOLUTION: 
<img width="1914" height="880" alt="image" src="https://github.com/user-attachments/assets/a07b144f-5e89-4abe-88e1-1bbc5d2449a2" />


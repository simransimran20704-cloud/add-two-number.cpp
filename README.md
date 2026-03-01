# Add Two Numbers (LeetCode)

This problem is about adding two numbers that are stored in linked lists.

Each node contains one digit.
The digits are stored in reverse order.

Example:
l1 = [2,4,3]
l2 = [5,6,4]

Output:
[7,0,8]

Because:
342 + 465 = 807


## Approach (Simple Words)

- I traversed both linked lists at the same time.
- I added the digits along with carry.
- I stored sum % 10 in a new node.
- I updated carry = sum / 10.
- Continued until both lists ended and carry became 0.


## Time Complexity
O(max(n, m))

## Space Complexity
O(max(n, m))


## What I Learned

- How to handle carry in linked list problems.
- How to use a dummy node.
- How to traverse two linked lists together.

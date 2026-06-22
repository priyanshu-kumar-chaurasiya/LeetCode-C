# 2. Add Two Numbers

## Problem
You are given two non-empty linked lists representing two non-negative integers.
The digits are stored in reverse order, and each node contains a single digit.

## Approach
- Traverse both linked lists simultaneously.
- Add corresponding digits along with the carry.
- Create a new node for each digit of the result.
- Continue until both lists and the carry are exhausted.

## Time Complexity
O(max(m, n))

## Space Complexity
O(max(m, n))
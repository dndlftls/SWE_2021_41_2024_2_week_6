# SWE_2021_41_2024_2_week_6

## Week 4 Assignment
- **Link of my repository**  
  [https://github.com/dndlftls/SWE_2021_41_2024_1_week_4/tree/main]

- **Description of my code**  
This code defines a function isHappy(n) to determine whether a number is a "happy number." A happy number is a number that, through a series of steps, eventually leads to 1 when replacing the number with the sum of the squares of its digits.

Code Breakdown:
Set Initialization (seen): A set seen is used to track numbers that have already been processed to detect cycles.

Outer Loop: The outer while n loop continues as long as n is not zero. Inside, it resets n and breaks the current value of n into its individual digits.

Sum of Squares: The inner while t loop takes each digit of n, squares it, and accumulates the sum back into n.

Cycle Detection: After computing the sum of squares for the digits, it checks if the new n has already been seen. If yes, the function breaks out of the loop, indicating a cycle.

Return Statement: If n becomes 1, it returns True, meaning the number is happy. If a cycle is detected, it returns False.

Example:
For n = 19, the process will go:

1^2 + 9^2 = 1 + 81 = 82
8^2 + 2^2 = 64 + 4 = 68
6^2 + 8^2 = 36 + 64 = 100
1^2 + 0 + 0 = 1
Since 1 is reached, 19 is a happy number.

---

## Week 5 Assignment

'''bash
dockeer exec ubuntu-container cat /exc/os-release
'''


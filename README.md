# Lone Sum

This repository contains `lone_sum`, a function that returns the sum of three integers, `a`, `b`, and `c`, with special rules for duplicates.

### Rules

- If all numbers are the same, return `0`.
- If two numbers are the same, return the unique value.
- If all numbers are different, return their sum.

### Example

```python
print(lone_sum(10, 10, 10))  # Output: 0
print(lone_sum(1, 2, 3))     # Output: 6
print(lone_sum(1, 2, 1))     # Output: 2
print(lone_sum(4, 5, 6))     # Output: 15
```

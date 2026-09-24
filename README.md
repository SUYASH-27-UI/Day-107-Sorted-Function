# Day-107-Sorted-Function
# Python Day 107 - Sorted Function

This program uses the `sorted()` function to create a sorted version of a list without changing the original list.

## Example

Original list:

```text
[40, 10, 30, 50, 20]
```

Sorted list:

```text
[10, 20, 30, 40, 50]
```

Original list after sorting:

```text
[40, 10, 30, 50, 20]
```

## Concepts Used

* List
* `sorted()` function
* Variables
* Ascending order
* Original list

## How It Works

1. A list of numbers is created.
2. The original list is displayed.
3. The `sorted()` function creates a new sorted list.
4. The new list is stored in `sorted_numbers`.
5. Both the sorted list and original list are displayed.
6. The original list remains unchanged.

## Python Code

```python
numbers = [40, 10, 30, 50, 20]

print("Original list:", numbers)

sorted_numbers = sorted(numbers)

print("Sorted list:", sorted_numbers)
print("Original list after sorting:", numbers)
```

## Output

```text
Original list: [40, 10, 30, 50, 20]
Sorted list: [10, 20, 30, 40, 50]
Original list after sorting: [40, 10, 30, 50, 20]
```

## Goal

The goal of this project is to understand the difference between `sort()` and `sorted()` and learn how to create a sorted copy of a list in Python.

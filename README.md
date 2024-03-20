# Binary Search Algorithm

## Overview
This is a simple Python implementation of the binary search algorithm. Binary search is an efficient algorithm for finding a target value within a sorted array. It works by repeatedly dividing the search interval in half until the target value is found or the interval is empty.

## Usage
To use the `binary_search` function:
1. Define a sorted list of values.
2. Define the left and right pointers indicating the start and end indices of the list.
3. Call the `binary_search` function with the sorted list, left pointer, right pointer, and the target value to search for.

Example:
```python
values = [77, 80, 102, 123, 288, 300, 540]
start_of_values = 0
end_of_values = len(values)
target = 288
result = binary_search(values, start_of_values, end_of_values, target)
print("Element {0} is located at index {1}".format(target, result))

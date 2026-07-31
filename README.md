# Insertion Sort

## Aim
Implement the Insertion Sort algorithm and analyze its time and space complexities.

## Programming Language
Python

## Algorithm
1. Start from the second element.
2. Store it as the key.
3. Compare it with previous elements.
4. Shift larger elements to the right.
5. Insert the key into the correct position.
6. Repeat until the array is sorted.

## How to Run

1. Install Python 3.
2. Save the file as `insertion_sort.py`.
3. Open a terminal in the project folder.
4. Run:

```bash
python insertion_sort.py
```

5. Enter the array elements separated by spaces.

## Sample Input

```
9 5 1 4 3
```

## Sample Output

```
Original Array: [9, 5, 1, 4, 3]
Sorted Array: [1, 3, 4, 5, 9]
```

## Time Complexity

| Case | Complexity |
|------|------------|
| Best | O(n), Θ(n), Ω(n) |
| Average | O(n²), Θ(n²), Ω(n²) |
| Worst | O(n²), Θ(n²), Ω(n²) |

## Space Complexity

O(1)

## Course Outcome

**CO1:** Analyze algorithms and express their time and space complexities using asymptotic notations.
Insertion Sort Algorithm

Objective

Implement the Insertion Sort algorithm and analyze its time and space complexities.

Programming Language

Python

Algorithm

1. Start from the second element of the array.
2. Store the current element as the key.
3. Compare the key with the previous elements.
4. Shift all elements greater than the key one position to the right.
5. Insert the key at its correct position.
6. Repeat the process until the entire array is sorted.

How to Run

1. Install Python 3.
2. Save the program as "insertion_sort.py".
3. Open the terminal or command prompt.
4. Navigate to the project folder.
5. Execute the command:
   python insertion_sort.py
6. Enter the number of elements.
7. Enter the array elements.
8. View the sorted output.

Sample Input

Enter the number of elements: 6
Enter the elements:
64
25
12
22
11
90

Sample Output

Sorted Array:
11 12 22 25 64 90

Time Complexity

Case| Complexity
Best Case| O(n), Θ(n), Ω(n)
Average Case| O(n²), Θ(n²), Ω(n²)
Worst Case| O(n²), Θ(n²), Ω(n²)

Explanation

- Best Case: The array is already sorted, requiring only one comparison for each element.
- Average Case: The elements are in random order, requiring comparisons and shifts.
- Worst Case: The array is in reverse order, requiring the maximum number of comparisons and shifts.

Space Complexity

O(1)

Insertion Sort is an in-place sorting algorithm, meaning it requires only a constant amount of extra memory.

Advantages

- Simple and easy to implement.
- Efficient for small datasets.
- Stable sorting algorithm.
- In-place sorting (requires constant extra space).
- Performs well for nearly sorted arrays.

Disadvantages

- Inefficient for large datasets.
- Average and worst-case time complexity is O(n²).
- Not suitable for large-scale sorting applications.

Course Outcome

CO1 – Analyze any given algorithm and express its time and space complexities using asymptotic notations.# Insertion-sort-algorithm-
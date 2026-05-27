# Heap Sort using Binary Heap Data Structure

## Project Title
Implementation and Analysis of Heap Sort Algorithm using Binary Heap Data Structure

---

## Overview
This project focuses on the design, implementation, and analysis of the Heap Sort algorithm using the Binary Heap data structure in the C programming language. Heap Sort is an efficient comparison-based sorting algorithm that guarantees `O(n log n)` time complexity in the best, average, and worst cases.

The project demonstrates:
- Heap construction using Binary Heap
- Heapify operation
- Sorting process using Heap Sort
- Time and space complexity analysis
- Test case execution and performance evaluation

---

## Features
- Implementation in C Programming
- In-place sorting algorithm
- Efficient `O(n log n)` performance
- Handles normal, edge, and extreme test cases
- Modular and well-commented code

---

## Technologies Used

| Component | Details |
|---|---|
| Language | C |
| Compiler | GCC |
| IDE | Visual Studio Code |
| Platform | Windows 10 |
| Libraries | stdio.h |

---

## Algorithm Used
### Heap Sort
Heap Sort works by:
1. Building a Max Heap from the input array
2. Repeatedly swapping the root element with the last element
3. Reducing heap size
4. Applying heapify to maintain heap property

---

## Time and Space Complexity

| Case | Complexity |
|---|---|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n log n) |
| Space Complexity | O(1) |

---

## Modules Identified

| Module | Description |
|---|---|
| Input Handler | Reads input from user |
| Heapify Module | Maintains heap property |
| Heap Construction | Builds Max Heap |
| Heap Sort Module | Performs sorting |
| Output Module | Displays sorted array |

---

## Sample Input
```text
Enter number of elements: 5
Enter elements:
5 3 8 1 2
```

## Sample Output
```text
Sorted Array:
1 2 3 5 8
```

---

## Compilation and Execution

### Compile
```bash
gcc heapsort.c -o heapsort
```

### Run
```bash
./heapsort
```

---

## Applications
- Operating System Scheduling
- Database Systems
- Priority Queues
- Artificial Intelligence
- Machine Learning
- Graph Algorithms

---

## Future Enhancements
- Parallel Heap Sort implementation
- GUI visualization of Heap operations
- Iterative heapify optimization
- Large-scale dataset processing

---

## References
1. Introduction to Algorithms – Cormen et al.
2. The Art of Computer Programming – Donald Knuth
3. GeeksforGeeks – Heap Sort
4. Programiz – Heap Sort Algorithm

---

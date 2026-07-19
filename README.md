Heap Data Structures: Implementation, Analysis, and Applications
Student Information
•	Student Name: Murali Krishna Vattikunta
•	Course: Algorithms and Data Structures (MSCS-532-B01) 
•	Assignment: Heapsort Implementation and Priority Queue Applications

Project Overview
This project consists of two independent implementations completed in Python using Jupyter Notebook.
Part 1: Heapsort Implementation and Analysis
This notebook implements the Heapsort algorithm using a binary max-heap. The implementation includes:
    •	Construction of a max heap
    •	Heapify operation
    •	Heapsort algorithm
    •	Time complexity analysis
    •	Space complexity analysis
    •	Empirical comparison with Quicksort and Merge Sort using different input sizes and input distributions (random, sorted, and reverse sorted)
    •	Discussion of the experimental results
    
Part 2: Priority Queue Implementation and Applications
This notebook implements a Priority Queue using a binary max-heap. The implementation includes:
    •	Task class for representing scheduled tasks
    •	Priority Queue implementation using a Python list
    •	Insert operation
    •	Extract Maximum operation
    •	Increase Key operation
    •	Empty queue check
    •	Sample execution demonstrating all operations
    •	Analysis of the time complexity of each operation
    
Assignment/:

•	Heapsort Implementation.ipynb
•	Priority Queue Implementation.ipynb
•	Heapsort_PriorityQueue_Analysis
•	README.md

Software Requirements
•	Python 3.x
•	Jupyter Notebook

Python Libraries Used
•	random
•	time

How to Run
1.	Open Jupyter Notebook.
2.	Open Heapsort Implementation.ipynb.
3.	Run all cells sequentially to execute the Heapsort implementation, empirical comparison, and analysis.
4.	Open Priority Queue Implementation.ipynb.
5.	Run all cells sequentially to execute the Priority Queue implementation and view the sample output.
   
Expected Output
Part 1
The notebook displays:
•	Sorted output using Heapsort
•	Execution times for Heapsort, Quicksort, and Merge Sort
•	Comparison of running times for random, sorted, and reverse-sorted datasets
•	Complexity analysis and discussion

Part 2
The notebook displays:
•	Insertion of sample tasks
•	Current heap after insertion
•	Highest-priority task extracted
•	Heap after extraction
•	Priority update using the Increase Key operation
•	Final extraction order of all remaining tasks
Complexity Summary
Heapsort
Operation	Complexity
Build Heap	O(n)
Sorting	O(n log n)
Best Case	O(n log n)
Average Case	O(n log n)
Worst Case	O(n log n)
Auxiliary Space	O(1)*

The recursive implementation of heapify() uses an additional recursion stack of O(log n).
Priority Queue
Operation	Complexity
Insert	O(log n)
Extract Maximum	O(log n)
Increase Key	O(n) (current implementation)
Is Empty	O(1)

Notes
•	Both implementations are written entirely in Python.
•	A binary max-heap is used as the underlying data structure in both parts.
•	Sample test cases are included within each notebook to demonstrate correctness.
•	The results and analyses are consistent with the theoretical properties of binary heaps and priority queues.


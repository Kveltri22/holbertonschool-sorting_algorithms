0x1A. C - Sorting algorithms & big O

General

Four different sorting algorithms. What is the big O notation, and how to evaluate the time complexity. How to select the best sorting algorithm for a given input. What is a stable algorithm.

Bubble Sort: Bubble sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order. The pass through the list is replaced until the list is sorted. Bubble sort has a time complexity of O(n^2).

Merge Sort: Merge sort is a divide -and-conquer algorithm that recursively divides the input list into smaller sub-lists, sorts those sub-lists, and then merges them back together. Merge sort has a time complexity of O(n^2).

Quick Sort: Quick sort is another divide-and-conquer algorithm that selects an element called the pivot and partitions the list around the pivot. It then recursively sorts the sub-lists on either side of the pivot. Quick sort has an average time complexity of O(n log n), but can have a worst-case time complexity of O(n^2).

Insertion Sort: Insertion sort is a simple sorting algorithm that builds the final sorted list one item at a time. It iterates through the input list, comparing each item to the ones before it and inserting it into the correct position. Inserting sort has a time complexity of O(n^2), but can be more efficient than other algorithms for small lists or partially sorted lists.

Sorting Algorithm README

This repository contains implementations of several sorting algorithms in the C language, along with animations to help visualize how they work. The sorting algorithms included are:

Bubble sort
Selection sort
Insertion sort
Merge sort
Quick sort
Each sorting algorithm is implemented in its own separate file, with a main function that demonstrates its use by sorting an array of integers. The implementation of each sorting algorithm includes functions to print the array before and after sorting, to aid in understanding how the algorithm works.

Big O Notation

Big O notation is used to describe the time complexity of an algorithm, or how its running time scales with the size of the input. The time complexity of each sorting algorithm implemented in this repository is as follows:

Bubble sort: O(n^2)
Selection sort: O(n^2)
Insertion sort: O(n^2)
Merge sort: O(n log n)
Quick sort: O(n log n)
Sorting Algorithm Animations

The animations included in this repository use the ncurses library to display the sorting process in real time. Each animation shows the input array, with the currently selected elements highlighted in red, and the sorted elements highlighted in green.

To run the animations, simply compile the C file of the desired sorting algorithm using your preferred C compiler, and run the resulting executable. The animation should begin automatically.

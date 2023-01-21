Sorting algorithms
& Big O Notation

This project aims to learn about the main sorting algorithms: Bubble Sort, Insertion Sort, Selection Sort and Quick Sort; while evaluating the time and space complexity of each designed algorithm and the Big O notation in C language.

Overview
Holberton School teaches Full-Stack Software Engineering with a project-based approach. Sorting algorithms & Big O Notation is one of the main projects of the second trimester that covers the High-level programming of Software Engineering.

Requirements
To run the algorithms you need to download the code files by clicking Download sorting_algorithms. Or by cloning this repository with the following command in your command terminal. The result will be the same regardless of the option you choose.

~$ git clone <https://github.com/karivone/sorting_algorithms.git>
The compilation process uses GNU Compiler Collection (GCC) and a Linux environment like Ubuntu 20.04 LTS. Enter the sorting_algorithms folder and use the makefile as follows.

Invocation
Each invocation of the make command executes a different algorithm with its respective printout on the console.

0. Bubble Sort
The 0-bubble_sort.c function sorts an array of integers in ascending order using the Bubble sort algorithm.

~/sorting_algorithms$ make bubble
Output

19, 48, 99, 71, 13, 52, 96, 73, 86, 7
19, 48, 71, 99, 13, 52, 96, 73, 86, 7
19, 48, 71, 13, 99, 52, 96, 73, 86, 7
19, 48, 71, 13, 52, 99, 96, 73, 86, 7
19, 48, 71, 13, 52, 96, 99, 73, 86, 7
19, 48, 71, 13, 52, 96, 73, 99, 86, 7
19, 48, 71, 13, 52, 96, 73, 86, 99, 7
19, 48, 71, 13, 52, 96, 73, 86, 7, 99
19, 48, 13, 71, 52, 96, 73, 86, 7, 99
19, 48, 13, 52, 71, 96, 73, 86, 7, 99
19, 48, 13, 52, 71, 73, 96, 86, 7, 99
19, 48, 13, 52, 71, 73, 86, 96, 7, 99
19, 48, 13, 52, 71, 73, 86, 7, 96, 99
19, 13, 48, 52, 71, 73, 86, 7, 96, 99
19, 13, 48, 52, 71, 73, 7, 86, 96, 99
13, 19, 48, 52, 71, 73, 7, 86, 96, 99
13, 19, 48, 52, 71, 7, 73, 86, 96, 99
13, 19, 48, 52, 7, 71, 73, 86, 96, 99
13, 19, 48, 7, 52, 71, 73, 86, 96, 99
13, 19, 7, 48, 52, 71, 73, 86, 96, 99
13, 7, 19, 48, 52, 71, 73, 86, 96, 99
7, 13, 19, 48, 52, 71, 73, 86, 96, 99
7, 13, 19, 48, 52, 71, 73, 86, 96, 99

1. Insertion sort
The 1-insertion_sort_list.c function sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm.

~/sorting_algorithms$ make insertion
2. Selection Sort
The 2-selection_sort.c function sorts an array of integers in ascending order using the Selection sort algorithm.

~/sorting_algorithms$ make selection
3. Quick sort
The 3-quick_sort.c function sorts an array of integers in ascending order using the Quick sort algorithm.

~/sorting_algorithms$ make quick
Files Description
test/*main*.c - Main files in charge of the test executions of the algorithm functions.
0-O — Big O Notation for the Bubble Sort Algorithm
0-bubble_sort.c — Function implementation of the Bubble Sort Algorithm
1-O — Big O Notation for the Insertion Sort Algorithm
1-insertion_sort_list.c — Function implementation of the Insertion Sort Algorithm using a double linked list
2-O — Big O Notation for the Selection Sort Algorithm
2-selection_sort.c — Function implementation of the Selection Sort Algorithm
3-O — Big O Notation for the Quick Sort Algorithm
3-quick_sort.c — Function implementation of the Quick Sort Algorithm
makefile - Script to compile and run the algorithm functions.
README.md — Project's description
print_array.c — Function to print all the arrays
print_list.c— Function to print the linked list
sort.h— Main header of the program
Authors
Karivone

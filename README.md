# DSP
Exploration and Implementations of various algorithms in golang.

### Goals
This repo is a small study project for Data Structures and algorithms some of the following topics will be approached

- Constructing and traversing data structures.
- Implementing system routines
- Distilling large data sets into single values
- Transforming one data set into another.

To break this down these specific issues will be tackled.

## Algorithms
- Big-O analysis of code and algorithms
- Sorting
- Hashing
- Handling large amounts of data
    - Difficulties of doing this
    - Considerations
    - Current approaches to large data set algorithms
        - Concurrency?
        - Sharding?
        - Etc etc.


### Sorting
> Worth noting that algorithms are considered tools, so it is mainly a case of weighing benefits over issues when using one of them.
>
> This is to say that there is no one-size-fits-all approach to sorting, and it heavily depends on the input and expected output.
- merge sort
    - splits the array into halves, recursively sorts each half, and then merges the sorted halves.
- heap sort
    - Uses a binary heap data structure to repeatedly extract the maximum (or minimum) element and maintain the heap property.
- quick sort
    - A divide-and-conquer algorithm that partitions the array around a pivot and recursively sorts the partitions.
    - Worst case is O(N^2)
    - Avg case is 0(N log N)
- tim sort
    - Hybrid sorting algorithm (used in Python’s and Java’s standard library) based on merge sort and insertion sort. It is optimized for real-world data, especially nearly sorted arrays.
- intro sort
    - A hybrid algorithm that combines quicksort, heapsort, and insertion sort. It switches to heapsort if recursion depth exceeds a certain limit.

### Data structures

#### Overview of NP-Complete problems
- Travelling salesman
- Knapsack problem

#### Structures
- Trees
    - Basic tree construction
    - Traversal & Manipulation algorithms
        - Breadth first search
        - Depth first search
        - Inorder traversal
        - Post-Order Traversal
        - Pre-Order Traversal
    - Types of trees
        - binary
        - n-ary
        - trie
    - Balanced trees and their implementations
        - Red/Black
        - Splay
        - AVL
- Hash Tables
- Stacks
- Arrays
- Linked lists
- Priority queues

#### Hash maps
Incredibly important data structure

- Implementation
- O() characteristics for golang's implementation of hashmaps
- Custom implementation in golang

### Graphs
How to represent graphs in memory/programmatically

- Objects and pointers
- Matrix
- Adjacency lists

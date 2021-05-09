# Heap
A Heap is a special Tree-based data structure in which the tree is a complete binary tree. Generally, Heaps can be of two types:
* Max-Heap: In a Max-Heap the key present at the root node must be greatest among the keys present at all of it’s children. The same property must be recursively true for all sub-trees in that Binary Tree
* Min-Heap: In a Min-Heap the key present at the root node must be minimum among the keys present at all of it’s children. The same property must be recursively true for all sub-trees in that Binary Tree

## Heap is based on
* [vector](https://github.com/itay-adi/DataStructures/tree/main/vector)
* [heap sort](https://github.com/itay-adi/DataStructures/blob/main/heap/heap_sort.c)

## heapify:
heap util file, contains funtions to support Heap DS. Includes:
* HeapifyUp - re-arranges the array to have a heap property, going bottom-up
* HeapifyDown - re-arranges the array to a have heap property, going up-bottom

## Operations on heap
* Push - adds an element to the heap.
* Pop - removes the top element of the heap. 
* Peek - displays the first element of heap which is the min / max value
* Remove - removes given element from the heap a pointer to it.

## heap implemintation consist 6 files:
* [heap.h](https://github.com/itay-adi/DataStructures/blob/main/heap/heap.h), [heapify.h](https://github.com/itay-adi/DataStructures/blob/main/heap/heapify.h): two header files
* [heap.c](https://github.com/itay-adi/DataStructures/blob/main/heap/heap.c), [heapify.c](https://github.com/itay-adi/DataStructures/blob/main/heap/heapify.c): functions implemintation
* [heap_test.c](https://github.com/itay-adi/DataStructures/blob/main/heap/heap_test.c): for a functionality testing
* [heap_sort.c](https://github.com/itay-adi/DataStructures/blob/main/heap/heap_sort.c): sorting algoritm using the heapifies

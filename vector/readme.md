# Vactor
Dynamic vector is a random access dynamic array.

## Attributes
* Capacity is a user given value
* Can hold pointers to any type of data, including structs
* All Operations are amortized O(1)

## Main operations on vector
* VectorGetElement - Retrieves the value of the element at a specific index
* VectorPushBack - adds an element to the end of the size of the vector
* VectorPopBack - removes the last element that was not yet removed
* VectorSetElement - sets the value of the element at a specific index
* VectorReserve - reallocates memory to the new capacity
* VectorShrinkToFit - shrinks capacity of the memory to the current size
* VectorSize - returns the current size of the vector
* VectorCapacity - returns the capacity of the vector

## Stack implemintation consist 3 files:
* [vector.h](https://github.com/itay-adi/DataStructures/blob/main/vector/vector.h): a header file
* [vector.c](https://github.com/itay-adi/DataStructures/blob/main/vector/vector.c): function implemintations
* [vector_test.c](https://github.com/itay-adi/DataStructures/blob/main/vector/vector_test.c): for a functionality testing

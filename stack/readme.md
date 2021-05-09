# Stack

## Policy
Stack is a LIFO policy structure.

## Attributes
* Capacity is a user given value
* Can hold pointers to any type of data, including structs
* All Operations are in O(1)

## Operations on stack
* Push - adds an element to the stack
* Pop - removes the most recently added element that was not yet removed
* Peek - looks at the most recently added element on the stack and returns a pointer to it

## Stack implemintation consist 4 files
* [stack.h](https://github.com/itay-adi/DataStructures/blob/main/stack/stack.h): a header file
* [stack.c](https://github.com/itay-adi/DataStructures/blob/main/stack/stack.c): functions implemintation
* [stackB.c](https://github.com/itay-adi/DataStructures/blob/main/stack/stackB.c): extra functions for minimum stack
* [stack_test.c](https://github.com/itay-adi/DataStructures/blob/main/stack/stack_test.c) for a functionality testing

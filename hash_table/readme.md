# hash table

A hash table is an unordered collection of key-value pairs, where each key is unique.
Hash tables offer a combination of efficient lookup, insert and delete operations.

* Is based on [dlist](https://github.com/itay-adi/DataStructures/tree/main/dlist)

## Main Operation
* HashSize - return the number of elements in the HashTable. O(n)
* HashTableSize - return the size of the HashTable. O(1)
* HashBucketSize - return the size of a specific bucket. O(n)
* HashIsEmpty - checks if the hashTable is empty. O(n)
* HashInsert - insert a member to the table. O(1) (Might be O(n) if the capacity of HashTableSize is low)
* HashFind - find an element in the hashTable. O(1)
* HashRemove - removes an element from the hashTable O(1)
* HashForEach - perform an action on each of the elements in the hashTable O(1)
* FindIndex - finds an index of a specific element

## hash_table implemintation consist 3 files
* [hash_table.h](https://github.com/itay-adi/DataStructures/blob/main/hash_table/hash_table.h): a header file
* [hash_table.c](https://github.com/itay-adi/DataStructures/blob/main/hash_table/hash_table.c): functions implemintation
* [hash_table_test.c](https://github.com/itay-adi/DataStructures/blob/main/hash_table/hash_table_test.h): for a functionality testing

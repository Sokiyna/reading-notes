# Hash Table 




In computing, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found.




## Hash Table component 

**Key: The idea of hashing is to distribute entries (key/value pairs) uniformly across an array. Each element is assigned a key (converted key). By using that key you can access the element in O(1) time. Using the key, the algorithm (hash function) computes an index that suggests where an entry can be found or inserted.**




**Value: In a hash table, data is stored in an array format, where each data value has its own unique index value. ... Thus, it becomes a data structure in which insertion and search operations are very fast irrespective of the size of the data.**




### Hashing Life Examples

In universities, each student is assigned a unique roll number that can be used to retrieve information about them.
In libraries, each book is assigned a unique number that can be used to determine information about the book, such as its exact position in the library or the users it has been issued to etc.

###  Hash Tables VS Trees

Hashing and trees perform similar jobs, but various factors in your program determine when to use one over the other.

Trees are more useful when an application needs to order data in a specific sequence. Hash tables are the smarter choice for randomly sorted data due to its key-value pair organization.

Hash tables can perform in constant time, while trees usually work in O(log n)O(logn). In the worst-case scenario, the performance of hash tables can be as low as O(n)O(n). An AVL tree, however, would maintain O(log n)O(logn) in the worst case. An efficient hash table requires a hash function to distribute keys. A tree is simpler, since it accesses extra space only when needed and does not require a hash function.


### Internal Methods

Add() : When adding a new key/value pair to a hashtable.
Find() : “The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value”.
Contains() : “The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned”.
GetHash() : “The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed”.






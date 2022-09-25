# Hash Tables
>This is a data structure used to store information in the form of key and value.It implements an associative array or a dictonary.Not all dictonaries are implemented using hash tables.There is a huge difference though between a dictonary and a hashtable.
>A hash table  maps keys to values by taking the hash value of the key (by applying some hash function to it) and mapping that to a bucket where one or more values are stored.
>A **hash function ** on the other hand takes in a key and returns an index of the key. If the key is already taken, it creates a linked list of the indexes one pointing to the other.  We can also define a hash function as any function that can be used to map data of arbitrary size to fixed size values.
> **Collision ** in a hash table can be defined as where two or more pieces of data in a hash table share the same value.

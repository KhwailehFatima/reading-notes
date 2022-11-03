# Hash Table

### Hashing (Hash Function)

In a hash table, a new index is processed using the keys. And, the element corresponding to that key is stored in the index. This process is called hashing.

Let k be a key and h(x) be a hash function.

Here, h(k) will give us a new index to store the element linked with k.


A hash table is an implementation of an associative array, a list of key-value pairs that allow you to retrieve a value via a key. Internally a hash table utilizes a hash function to transform a key value into an index that points to where the value is stored in memory. Hash tables have fast search, insertion and delete operations.

### Hash Collision

When the hash function generates the same index for multiple keys, there will be a conflict (what value to be stored in that index). This is called a hash collision.


stored in that index). This is called a hash collision.

We can resolve the hash collision using one of the following techniques.

* Collision resolution by chaining
* Open Addressing: Linear/Quadratic Probing and Double Hashing



### There are two main ways to implement a hash table/associative array in JavaScript.



#### Using the Object Data Type
The simplest implementation is using the Object data type. This is because all non-scalar objects in JavaScript behave as associative arrays, a mapping from property keys to values. So an Object itself can behave as a basic hash table.

#### Using a Map Object

The Map object was created to implement this type of associative array without some of the downsides of using a basic Object:

There are no pre-existing keys that could result in a collision
A Map object has a size property to track its contents.
A Map object can have keys that are any data type.
A Map has been optimized for repeated addition and insertion of key-value pairs.
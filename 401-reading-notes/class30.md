# Hashtables

## What is a Hashtable?

Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

* The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value.

*  A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

* Hash maps take advantage of an array’s O(1) read access. Instead of adding elements to an array from beginning to end, a hash map uses a “hash function” to place each item at a precise index location, based off it’s key.

* A collision occurs when more than one key hashes to the same index in an array. As mentioned earlier, a “perfect hash” will never have any collisions. To put this into perspective, the worst possible hash is one that hashes every single key to the same exact index of an array. The more keys you have hashed to a specific index, the more key/value pair combos you can potentially have.

* Collisions are solved by changing the initial state of the buckets. Instead of starting them all as null we can initialize a LinkedList in each one! Now if two keys resolve to the same index in the array then their key/value pairs can be stored as a node in a linked list. Each index in the array is called a “bucket” because it can store multiple key/value pairs

* Hash maps do this to read value:

    * accept a key
    * calculate the hash of the key
    * use modulus to convert the hash into an array index
    * use the array index to access the short LinkedList     representing a bucket
    * search through the bucket looking for a node with a     key/value pair that matches the key you were given

* Hash Maps can have any number of buckets. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

### Internal Methods

* Add()
When adding a new key/value pair to a hashtable:

   * send the key to the GetHash method.
   * Once you determine the index of where it should be
     placed, go to that index
   * Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
   * If something does exist, add the new key/value pair to the data structure within that bucket.


* Find()

The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

* Contains()

The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

* GetHash()

The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

---------
### refrences : 

* [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
# Implementation: Hash Tables

* Use an analogy
- A hash table is analogous to an array whose index is calculated with a hashing function to identify a space in memory uniquely. localStorage is an example of a data structure based on a hash table.

* Explain a detail in depth


* Use WHY, WHAT, HOW structure
- you can use hash tables allow you to search. and inset in the tables for ease of use

* Tutorial / walk through an example


* Write a quiz


* Create a vocabulary/definition list
- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

* Write a cheat sheet
- Hashing is implemented in two steps:

An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
The element is stored in the hash table where it can be quickly retrieved using hashed key.

hash = hashfunc(key)
index = hash % array_size

In this method, the hash is independent of the array size and it is then reduced to an index (a number between 0 and array_size − 1) by using the modulo operator (%).

- 

* Create a diagram / visualization / cartoon of a topic


* Anthropomorphize the concepts, and write a conversation between them


* Build a map of the information


* Construct a fill-in-the-blank worksheet for the topic

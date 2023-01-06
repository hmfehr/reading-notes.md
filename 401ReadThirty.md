# Implementation: Hash Tables

* Use an analogy
- A hash table is analogous to an array whose index is calculated with a hashing function to identify a space in memory uniquely. localStorage is an example of a data structure based on a hash table.

* what is a hashtable
- a structure (an array in js) that stores key value pairs.
- we find a way to translate the key(hash into an index in the array


* Use WHY, WHAT, HOW structure
- you can use hash tables allow you to search. and inset in the tables for ease of use
- why: hashing can add security, but not the main reasin why
* performant lookup
* constant O(1) lookup

* Tutorial / walk through an example


* Write a quiz


## * Create a vocabulary/definition list
- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.
### class vocab
- key: (what we can hash) - sometimes this might be a primitive, could also be an object (possibly - see language docs)
- hashing: pass in a string, return that hasshed sting as a number. the number translates to a spacific or deterministic place within our structure (hashtable)
- collision: if a key hashed to the same location in our structure, we call that a collision
  - the more perfect hash you have, the less likley you are to have collisions
- bucket: a linked list (structure) built at the index in our HashTable to hold multiple keys (collisions could happen)

* Write a cheat sheet
- Hashing is implemented in two steps:

An element is converted into an integer by using a hash function. This element can be used as an index to store the original element, which falls into the hash table.
The element is stored in the hash table where it can be quickly retrieved using hashed key.

hash = hashfunc(key)
index = hash % array_size

In this method, the hash is independent of the array size and it is then reduced to an index (a number between 0 and array_size − 1) by using the modulo operator (%).

- 

* Create a algorithm / visualization / cartoon of a topic
 example:
 ```javascript
 `ASCII sum of "Hunter"` = 410.
 410 * 599 = 245590
 245590 % 1024 = 854
 //'Hunter' would hash to a location of 854
 ```


* Anthropomorphize the concepts, and write a conversation between them


* Build an algorithm of the information
- the goal is to input a key, and output a llocation in our HashTable
- decide the "size", aka how any indexes in the array: '1024'
- turn the key into a string
  - convert string characters into ASCII values
  - sum all of the ASCII value
  - multiply our sum by a large primary number '599'
  - take that product and get the '%' (modulu) when divided by the number of buckets ('1024')

* Construct a fill-in-the-blank worksheet for the topic

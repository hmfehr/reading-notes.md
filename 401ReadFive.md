# Linked Lists


## Big 0

* Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:

* Running Time (also known as time efficiency / complexity)
The amount of time a function needs to complete.

* Memory Space (also known as space efficiency / complexity)
The amount of memory resources a function uses to store data and instructions.

* Big O’s role in algorithm efficiency is to describe the Worst Case of efficiency an algorithm can have in performing it’s job.

4 Key Areas for analysis:

* Input Size
* Units of Measurement
* Orders of Growth
* Best Case, Worst Case, and Average Case

In order to quantify the Running Time in our analysis, we will consider Three Measurements of time:

* The time in milliseconds from the start of a function execution until it ends.
- For the purposes of Big O, we won’t be considering this measurement since different machines will have different individual run times depending on how powerful they are. Regardless, this will always be a measurement of run-time.

* The number of operations that are executed.
- Think of this as the number of lines of code that are executed from start to finish of a function.

* The number of “Basic Operations” that are executed.
- “Basic Operation” refers to the operation that is contributing the most to the total running time. This is usually the most time consuming operation within the inner most loop.

## Linked Lists

* A Linked List is a sequence of Nodes that are connected/linked to each other.

* Linked List - A data structure that contains nodes that links/points to the next node in the list.
* Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
* Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
* Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
* Next - Each node contains a property called Next. This property contains the reference to the next node.
* Head - The Head is a reference of type Node to the first node in a linked list.
* Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.



























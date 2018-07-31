#### Borrowed from http://www.thagomizer.com/blog/2016/05/06/algorithms-queues-and-stacks.html

This is part of the series on algorithms and data structures called “Algorithms with Auntie Aja”. This series provides an introduction data structures and algorithms for folks who never learned it or have forgotten it.

### Stacks
A stack is one of the simplest data structures. It is just like a pile of playing cards or a stack of plates. When you add something to the pile you put it on top of all the things that are already there. When you take something away you remove it from the top of the stack. Computer Science uses specialized terms for things like this though. So instead of add we say push, and instead of remove we say pop. Another term you may hear with regards to stacks is LIFO which stands for Last In First Out. With a stack the last thing you added in the first thing that is removed.

##### Stack Push
<img src="http://www.thagomizer.com/img/StackPush.gif">

##### Stack Pop
<img src="http://www.thagomizer.com/img/StackPop.gif">

### Queues
You probably have experience with physical queues at amusement parks, concerts, or sports arenas. In the US, we usually call them lines. A queue is an ordered collection (or group) where we add things to one end (called the tail) and we remove things from the other end (called the head). Adding things to a queue is called enqueueing. Removing items from a queue is called dequeueing. This is also called FIFO for first in, first out.

##### Queue Add
<img src="http://www.thagomizer.com/img/QueueAdd.gif">

##### Queue Remove
<img src="http://www.thagomizer.com/img/QueueRemove.gif">


#### Conclusion and Bonus
These two data structures are the heart of Breadth-First Search and Depth-First Search. In turn those algorithms can be used to solve mazes, build minesweeper, and solve a large number of path-finding problems. The next post will explain those algorithms and show how they use these data structures.

If you want to play around with data structures more, try implementing a stack or a queue using a linked list instead of an array. If you get stuck try drawing out your linked list on paper and walking through a simple test case. It is what I do and it usually helps.


# Dijkstra's Deque
This final project for Advanced CS is actually _two_ different projects. The
first task is to code what is called a _Deque_ (see below) and the second is
to use a stack (which you have already coded, of course) to implement
Dijkstra's Algorithm for the evaluation of algebraic expressions (also below).
Please read all of the specifications carefully before you begin.

# Deque

The word "Deque" is an abbreviation for "Double-Ended Queue" and is a kind of
cross between stacks and queues. Their distinguishing feature is that items can
be added and taken from _both_ sides. For the sake of this project we will term
these sides _left_ and _right_, but they are sometimes called "start" and "end"
as well.


Your Deque must be fully generic (it must make sufficient use of generic type
variables in its definition, and implement the following API:

``public Deque()`` which constructs an empty Deque of type T.

``public boolean isEmpty()`` which returns whether or not the Deque is currently
empty (contains no elements). This is true for a newly-initialized Deque (and
other empty deques).

``public int size()`` which returns the number of elements in the deque.

``public void addLeft(T item)`` which adds the specified item to the _left_ end
of the queue.

``
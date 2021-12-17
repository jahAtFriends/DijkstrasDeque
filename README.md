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
of the dequeue.

``public void addRight(T item)`` which adds the specified item to the _right_
end of the deque.

``public T removeLeft()`` which returns and removes the leftmost item in the
deque.

``public T removeRight()`` which returns and removes the rightmost item in the
deque.

``public Iterator<T> iterator()`` which returns an iterator over the elements
of the deque. **Important**: for the sake of this project the _left_ end is
considered to be the start of the deque and the right the end. Hence an
iterator over the deque should return the elements in _left-to-right_ order.
# ConcurrentModificationException in Java

This repository demonstrates a common error in Java: the ConcurrentModificationException.  The example code attempts to modify an ArrayList while iterating over it using a for-each loop, which leads to this exception.

The solution demonstrates how to safely modify a list during iteration, avoiding the exception.  This is done by using an Iterator and its `remove()` method.

This is a good example of a common concurrency issue in Java. 
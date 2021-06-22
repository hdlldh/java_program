# Week 1: Threads and Locks
## 1.1 Java Threads
* Wikipedia article on [Threads](https://en.wikipedia.org/wiki/Thread_(computing))
* [Tutorial on Java threads](https://docs.oracle.com/javase/tutorial/essential/concurrency/runthread.html)
* [Documentation on Thread class in Java 8](https://docs.oracle.com/javase/8/docs/api/java/lang/Thread.html)

## 1.2 Structured Locks
* [Tutorial on Intrinsic Locks and Synchronization in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/locksync.html)
* [Tutorial on Guarded Blocks in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/guardmeth.html)
* Wikipedia article on [Monitors](https://en.wikipedia.org/wiki/Monitor_(synchronization))

## 1.3 Unstructured Locks
* [Tutorial on Lock Objects in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/newlocks.html)
* [Documentation on Java’s Lock interfaces](http://docs.oracle.com/javase/7/docs/api/java/util/concurrent/locks/Lock.html)

## 1.4 Liveness and Progress Guarantees
* [Deadlock example with synchronized methods in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/deadlock.html)
* [Starvation and Livelock examples in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/starvelive.html)
* Wikipedia article on [Deadlock and Livelock](https://en.wikipedia.org/wiki/Deadlock)

## 1.5 Dining Philosophers Problem
* Wikipedia article on the [Dining Philosophers Problem](https://en.wikipedia.org/wiki/Dining_philosophers_problemW)

# Week 2: Critical Sections and Isolation
## 2.1 Critical Sections
* Wikipedia article on [Critical Sections](https://en.wikipedia.org/wiki/Critical_section)
* Wikipedia article on [Atomicity](https://en.wikipedia.org/wiki/Atomicity_(database_systems))

## 2.2 Object-Based Isolation
* Wikipedia article on [Monitors](https://en.wikipedia.org/wiki/Monitor_(synchronization))

## 2.3 Spanning Tree Example
* Wikipedia article on [Spanning Trees](https://en.wikipedia.org/wiki/Spanning_tree)

## 2.4 Atomic Variables
* [Tutorial on Atomic Integers in Java](https://docs.oracle.com/javase/tutorial/essential/concurrency/atomicvars.html)
* Article in Java theory and practice series on [Going atomic](https://www.ibm.com/developerworks/library/j-jtp11234/)
* Wikipedia article on [Atomic Wrapper Classes in Java](https://en.wikipedia.org/wiki/Primitive_wrapper_class#Atomic_wrapper_classes)

## 2.5 Read-Write Isolation
* Wikipedia article on [Readers-writer lock](https://en.wikipedia.org/wiki/Readers%E2%80%93writer_lock)

# Week 3: Actors
## 3.1 Actor Model
* Wikipedia article on the [Actor Model](https://en.wikipedia.org/wiki/Actor_model)
* Documentation on the [Akka Actor Library](http://doc.akka.io/docs/akka/2.5.3/java/guide/index.html) (though Akka is not used in this course, it is a useful library to be aware of if you are interested in using the actor model with Java and Scala applications)

## 3.2 Actor Examples
* Wikipedia article on [Pipeline Parallelism](https://en.wikipedia.org/wiki/Pipeline_(computing))

## 3.3 Sieve of Eratosthenes
* Wikipedia article on the [Sieve of Eratosthenes problem](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)

## 3.4 Producer-Consumer Problem with Unbounded Buffer

## 3.5 Producer-Consumer Problem with Bounded Buffer
* Wikipedia article on the [Producer-Consumer problem](https://en.wikipedia.org/wiki/Producer%E2%80%93consumer_problem)

# Week 4: Concurrent Data Structures
## 4.1 Optimistic Concurrency
* Wikipedia article on [Optimistic concurrency control](https://en.wikipedia.org/wiki/Optimistic_concurrency_control)
* [Documentation on Java’s AtomicInteger class](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/atomic/AtomicInteger.html)

## 4.2 Concurrent Queues
* [Documentation on Java’s AtomicReference class](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/atomic/AtomicReference.html)
* [Documentation on Java's ConcurrentLinkedQueue class](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/ConcurrentLinkedQueue.html)

## 4.3 Linearizability
* [Wikipedia article on the Linearizability](https://en.wikipedia.org/wiki/Linearizability)

## 4.4 Concurrent HashMap
* [Documentation on Java’s ConcurrentHashMap class](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/ConcurrentHashMap.html)
* Wikipedia article on [Java’s ConcurrentMap interface](https://en.wikipedia.org/wiki/Java_ConcurrentMap)

## 4.5 Minimum Spanning Tree Example
* Wikipedia article on [Borvka’s algorithm](https://en.wikipedia.org/wiki/Bor%C5%AFvka%27s_algorithm) for finding a minimum cost spanning tree of an undirected graph

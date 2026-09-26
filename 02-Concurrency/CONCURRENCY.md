# Java Concurrency

## Status
Completed / strong.

Covered:
- `synchronized`
- `volatile`
- CAS
- AtomicInteger
- ReentrantLock
- ReadWriteLock
- StampedLock
- CountDownLatch
- CyclicBarrier
- Semaphore
- BlockingQueue variants
- ConcurrentHashMap
- `compute`
- `computeIfAbsent`

## Production emphasis

Understand the correctness problem first:
- race condition
- visibility
- ordering
- contention
- deadlock
- throughput
- coordination

Then choose the synchronization mechanism.

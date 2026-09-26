# Java Memory Model

## Status
Completed / strong.

## Core concepts
- Visibility
- Ordering
- Atomicity
- Happens-before

## Key tools
- `synchronized`
- `volatile`
- Atomic classes
- Locks

## Interview anchor

The JMM defines the rules under which one thread's actions become observable to another thread.

The most important interview relationship is:

```text
Happens-before
    ↓
Visibility + ordering guarantees
```

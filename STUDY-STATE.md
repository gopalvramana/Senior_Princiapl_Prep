# Study State

Last updated: 2026-10-05

## Current focus

**Core Java → Collections** (medium depth)

### Current subtopic
**HashMap internals**

### Collections sequence
1. ~~List fundamentals~~ — completed
2. ~~ArrayList vs LinkedList~~ — completed
3. Set fundamentals — conceptual pass
4. HashMap internals — next high-value Collections topic
5. TreeMap / TreeSet — conceptual
6. Concurrent collections — important concepts
7. Common Collections interview traps — short pass
8. Collections — complete

Do not expand Collections into exhaustive API-level study.

### Completed within Generics
- Why generics exist
- Generic classes
- Generic interfaces
- Generic methods
- Type inference
- Explicit type arguments
- Multiple type parameters
- `Function<T, R>`
- Type parameter bounds
- Upper bounds
- Multiple bounds
- `? extends`
- `? super`
- PECS — Producer Extends, Consumer Super
- Type erasure
- Erasure limitations
- `instanceof` and reifiable types
- Compiler-inserted casts
- Reference type vs actual object type
- Raw types vs wildcard types

## Recently completed

### Generics
Complete at Senior/Principal interview-prep depth. Bridge methods not covered in depth — revisit as part of interview traps if needed.

### JMM / Concurrency
Strong coverage:
- happens-before
- visibility
- ordering
- atomicity
- `synchronized`
- `volatile`
- CAS
- atomic classes
- locks
- coordination primitives
- blocking queues
- concurrent collections

### CompletableFuture
Strong coverage:
- `runAsync`
- `supplyAsync`
- `thenApply`
- `thenCompose`
- `thenCombine`
- `thenAccept`
- `thenAcceptBoth`
- `runAfterBoth`
- `allOf`
- `anyOf`
- exception handling
- executors
- CPU vs I/O pools
- common pool
- timeouts

### JVM
Partially covered and intentionally parked to improve breadth.

## Locked Interview Preparation Depth Strategy

The preparation uses different depth levels based on the interview value of each topic.

### Very Deep — Primary Differentiators
- System Design / Architecture
- Distributed Systems
- AWS / Cloud Architecture
- Kafka / Event-driven Architecture
- Principal-level Leadership / Behavioral

For these topics, preparation covers:
1. What is it?
2. Why does it exist?
3. How does it work internally?
4. Application / real-world usage
5. Failure modes
6. Performance and scalability
7. Alternatives
8. Trade-offs
9. Production examples
10. Principal-level follow-up questions
11. 60-90 second interview explanation

### Medium-Deep
- Java / Spring Boot
- JVM / Concurrency
- Databases
- Backend Engineering

Goal: Strong conceptual and internal understanding sufficient to handle Senior/Principal follow-up questions, with emphasis on production behavior, trade-offs, performance, and failure modes.

### Medium
- DSA
- Collections
- Generics

DSA goal: Focus on patterns rather than exhaustive problem solving. Target approximately 40-50 foundational problems. Emphasize recognizing patterns, explaining reasoning, and solving under interview pressure.

Collections and Generics: Achieve interview-ready conceptual understanding. Cover important internals and common traps. Avoid exhaustive API memorization and low-value implementation details.

### Light
- Java API trivia
- Exhaustive/low-value implementation details

Only cover these when they are commonly relevant to Senior/Principal interviews or directly support a higher-value concept.

### Preparation Principle

Do not spend disproportionate preparation time on low-value details.

The goal is not exhaustive Java knowledge. The goal is Principal-level engineering judgment, architecture capability, technical depth, and the ability to explain and defend decisions.

Standard for high-value topics:
Understand → Internal Mechanics → Application → Failure Modes → Performance → Trade-offs → Production Example → Principal Follow-ups → 60-90 sec Interview Answer

## Session style

- One small concept/question at a time.
- Interactive Q&A rather than large information dumps.
- Test reasoning, not memorization.
- When an answer is partially correct, identify exactly what is correct and refine it.
- Use unfamiliar/adversarial questions to fortify understanding.
- Move on when the topic has reached the required interview depth.
- Do not turn low-value topics into exhaustive study sessions.

## Current study cadence

**Understand → Practice → Lock → Move**

## Rules for future updates

When a topic is completed:
1. Update this file.
2. Add a dated entry to `PROGRESS-LOG.md`.
3. Update the relevant topic file.
4. Keep the next topic explicit.

Do not silently change the roadmap.

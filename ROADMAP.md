# Senior / Principal Java Preparation Roadmap

## Objective

Be interview-ready by the end of January 2027 for backend-heavy Lead / Principal Engineer roles.

## Study method

For each topic:

1. Core concept / mental model
2. One production-style example
3. Interview-relevant depth and traps
4. Move on

Avoid spending excessive time on syntax trivia or low-value API details. Use spaced repetition for completed topics.

---

## Phase 1 — Core Java

### Topics
- OOP and design principles
- Object contracts: `equals`, `hashCode`, `toString`
- Collections and internals
- `HashMap` / `ConcurrentHashMap`
- Generics
- Type erasure
- Wildcards and PECS
- Lambdas and functional interfaces
- Streams
- Exceptions
- Optional
- Immutability
- `final`, `static`
- Records
- Common Java interview traps

### Status
**In progress**

Current topic: Collections

Completed: Generics (type parameters, bounds, wildcards, PECS, type erasure, reifiable types, raw vs wildcard types)

---

## Phase 2 — Java Memory Model & Concurrency

### Topics
- JMM
- Happens-before
- Visibility
- Ordering
- Atomicity
- `synchronized`
- `volatile`
- CAS
- Atomic classes
- `ReentrantLock`
- Read/write locks
- `StampedLock`
- Coordination primitives
- `BlockingQueue`
- Concurrent collections

### Status
**Completed / strong**

---

## Phase 3 — CompletableFuture

### Topics
- Async pipelines
- Composition
- Combination
- Exception handling
- Executors
- CPU vs I/O workloads
- Timeouts
- `allOf` / `anyOf`
- Production patterns

### Status
**Completed / strong**

---

## Phase 4 — JVM Fundamentals

### Phases
1. JVM Mental Model
2. Class Loading
3. JVM Runtime Memory
4. Object Creation
5. Method Execution
6. Interpreter + JIT
7. Garbage Collection
8. JVM Threads
9. JVM Memory Beyond Heap
10. JVM Errors & Failure Modes
11. JVM Performance & Troubleshooting
12. Final Integration

### Status
**Partially completed / parked**

Covered:
- JVM mental model
- JDK / JRE / JVM
- Bytecode
- JVM architecture
- JNI
- Class loading basics
- Loading, linking, initialization
- Verification, preparation, resolution
- Bootstrap / Platform / Application class loaders
- Parent delegation
- Classpath
- Main-class startup model

Remaining:
- Class identity and class loaders
- `ClassNotFoundException` vs `NoClassDefFoundError`
- Runtime memory
- Object creation
- Method execution
- Interpreter / JIT
- GC
- JVM threads
- Native/off-heap memory
- JVM failure modes
- Performance troubleshooting
- Final integration

---

## Phase 5 — Spring / Spring Boot / Backend

- Spring Core / IoC / DI
- Bean lifecycle
- Configuration
- AOP
- Spring Boot
- REST API design
- Validation
- Exception handling
- Transactions
- Spring Data JPA
- Hibernate
- Caching
- Security fundamentals
- Production backend patterns

---

## Phase 6 — Messaging

- Kafka fundamentals
- Partitions
- Consumer groups
- Ordering
- Delivery semantics
- Offset management
- Rebalancing
- Idempotency
- Kafka Streams
- IBM MQ
- Enterprise messaging patterns

---

## Phase 7 — Distributed Systems

- Distributed system fundamentals
- Consistency
- Availability
- CAP
- Replication
- Partitioning
- Distributed transactions
- Idempotency
- Retry
- Timeout
- Circuit breaker
- Bulkhead
- Rate limiting
- Event-driven architecture
- Distributed data patterns

---

## Phase 8 — AWS / Cloud

- AWS core services
- EC2
- ALB
- Auto Scaling
- ECS / Fargate
- EKS
- S3
- RDS
- DynamoDB fundamentals
- IAM
- VPC
- CloudWatch
- Messaging
- Containers
- Kubernetes
- Cloud architecture

---

## Phase 9 — System Design

- Requirements clarification
- Capacity estimation
- API design
- Data modeling
- Scaling
- Caching
- Messaging
- Resilience
- Observability
- Security
- Consistency
- Failure modes
- Principal-level tradeoffs

Case studies:
- Payment system
- Order processing
- Notification platform
- Event ingestion
- Portfolio / financial-data system
- Enterprise integration platform

---

## Phase 10 — DSA

Focus on high-value patterns rather than exhaustive problem counts.

- Two pointers
- Sliding window
- Binary search
- DFS / BFS
- Trees
- Graphs
- Dynamic programming
- Backtracking
- Greedy
- Topological sort
- Union-Find
- Matrix manipulation

Target:
**40–50 foundational problems with strong pattern recognition.**

---

## Phase 11 — Leadership / Principal Skills

- Technical leadership
- Architecture ownership
- Stakeholder management
- Technical tradeoffs
- Influencing without authority
- Mentoring
- Handling ambiguity
- Production incidents
- Cross-team dependencies
- Architecture decision records
- Behavioral stories

---

## Phase 12 — Financial Domain

Targeted concepts for financial / investment technology roles:

- Time-weighted return
- Money-weighted return
- IRR
- Yield
- Income return
- Total return
- Portfolio concepts
- Basic investment-account concepts
- Relevant financial calculations

---

## Phase 13 — Python / AI Integration

- Python fundamentals for application development
- Python APIs
- Data processing
- AI integration
- LLM APIs
- RAG
- Embeddings
- Vector databases
- AI-assisted enterprise applications

---

## Phase 14 — Interview Readiness

- Java backend interviews
- System design interviews
- Principal-level architecture
- Coding rounds
- Behavioral / leadership
- Mock interviews
- Weak-area revision
- Final readiness assessment

---

## Current state — October 1, 2026

| Area | Status |
|---|---|
| JMM + Concurrency | Completed / Strong |
| CompletableFuture | Completed / Strong |
| JVM Fundamentals | Partially completed / Parked |
| Core Java | In progress |
| Generics | Completed |
| Collections | Current |
| DSA | Started |
| Spring / Backend | Not yet active |
| Messaging | Not yet active |
| Distributed Systems | Not yet active |
| AWS / Cloud | Not yet active |
| System Design | Not yet active |
| Leadership | Not yet active |
| Financial Domain | Not yet active |
| Python / AI | Not yet active |

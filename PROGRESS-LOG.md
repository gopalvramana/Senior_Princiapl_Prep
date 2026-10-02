# Progress Log

## 2026-10-01 — Generics completed

Restarted Generics from the beginning for stronger conceptual mastery.

Covered:
- Generic classes, interfaces, and methods
- Type inference and explicit type arguments
- Type parameter bounds and multiple bounds
- `? extends` and `? super`
- Generic invariance
- PECS
- Reference type vs actual object type
- `List<?>`
- Type erasure
- Erasure to Object / leftmost bound
- Compiler-inserted casts
- Why type erasure exists
- `instanceof` limitations and reifiable types
- Raw types vs wildcard types

Generics is now considered complete at the current Senior/Principal interview-prep depth.

Next: Collections.

---

## 2026-09-28

### Generics
- `? super` — lower-bounded wildcards complete
- PECS — Producer Extends, Consumer Super

Key mental model locked:
- Producer → `? extends` → safely read
- Consumer → `? super` → safely write

Current:
- Type erasure

---

## 2026-09-27

### Generics
- `? extends` — upper-bounded wildcards complete

Current:
- `? super`

---

## 2026-09-26

### Generics
Completed:
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

Current:
- Wildcards — `? extends`

### Preparation cadence
Adjusted to a faster breadth-plus-depth model:
- Core concept / mental model
- One production example
- Interview depth / traps
- Move on

### Repository
Established the repository structure as the persistent preparation knowledge base.

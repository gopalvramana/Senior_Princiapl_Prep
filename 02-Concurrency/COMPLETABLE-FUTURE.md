# CompletableFuture

## Status
Completed / strong.

## Covered

### Async
- `runAsync`
- `supplyAsync`

### Transformation
- `thenApply`
- `thenCompose`

### Combination
- `thenCombine`
- `thenAcceptBoth`
- `runAfterBoth`
- `allOf`
- `anyOf`

### Terminal / handling
- `thenAccept`
- `exceptionally`

### Production concerns
- CPU vs I/O executors
- common ForkJoinPool
- blocking tasks
- timeouts
- `orTimeout`
- `completeOnTimeout`

## Key distinction

```text
thenCompose = flatten dependent async stages
thenCombine = combine independent async results
```

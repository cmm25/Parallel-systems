# Speedup and Amdahl's Law

## Key Concept
Amdahl's Law describes the potential performance improvement of a computational task when only part of the system is enhanced.

## Formula Breakdown
```
Speedup = 1 / ((P/N) + S)
- P: Parallel fraction of the computation
- S: Serial fraction of the computation
- N: Number of processors
```

## Insights
- As N (processors) increases, speedup approaches a limit
- Not all tasks can be fully parallelized
- Serial portions create a "bottleneck" that caps performance improvement

## Example
- 50% parallelizable task on 4 processors
- Theoretical speedup: 1 / ((0.5/4) + 0.5) ≈ 2×
- Adding more processors yields diminishing returns

## Practical Implication
Improving parallel efficiency matters more than adding processors.
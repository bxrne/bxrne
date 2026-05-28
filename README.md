 Building [**Tau**](https://github.com/bxrne/tau) — a time-series database where time is modelled
  as a sequence of half-open intervals `[start, end)` with algebraically precise semantics.

  Corrections append as new layers; the newest layer wins at query time. Compaction normalises any
  stack of layers into a single canonical layer, every query result is identical before and after.
  The invariants are not asserted by hand: they are verified by property-based tests and a
  deterministic simulation tester that drives every configuration combination against a reference
  oracle.

  **→ [tau.bxrne.com](https://tau.bxrne.com)**

![](https://github.com/bxrne/stats/blob/generated/overview.svg#gh-dark-mode-only)
![](https://github.com/bxrne/stats/blob/generated/languages.svg#gh-dark-mode-only)

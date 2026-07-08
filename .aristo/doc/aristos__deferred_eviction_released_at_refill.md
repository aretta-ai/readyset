**Aristo verified intent — `aristos:deferred_eviction_released_at_refill`**

At release of a buffered upquery response for a key, an eviction obligation outstanding against that key is issued downstream as an eviction for the same key within that same release, discharged exactly once. The obligation is never carried past the release as a settled materialization left filled with stale replay contents.

<sub>Verify level: **full** · Server-bound (`aristos:` namespace) · See [parent: eviction_debt_conserved](./eviction_debt_conserved.md)</sub>

---

**Aristo verified intent — `eviction_cascade_reaches_all_downstream_materializations`**

Evicting a key propagates to every downstream materialization transitively derived from it, including those reachable only through the source-triggered path; no reachable downstream materialization retains a filled entry for the evicted key.

<sub>Verify level: **neural** · See [parent: eviction_preserves_holeness](./eviction_preserves_holeness.md)</sub>

---

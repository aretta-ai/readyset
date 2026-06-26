**Aristo verified intent — `cascade_gated_on_positive_freed_measure`**

The downstream eviction cascade for a key is initiated exactly when evicting that key from the local materialization freed a strictly positive memory measure, which holds precisely when the eviction removed a present key.

<sub>Verify level: **full** · See [parent: eviction_preserves_holeness](./eviction_preserves_holeness.md)</sub>

---

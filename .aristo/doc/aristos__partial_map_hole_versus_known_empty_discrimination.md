**Aristo verified intent — `aristos:partial_map_hole_versus_known_empty_discrimination`**

A key reads as a re-fillable hole precisely when no row is stored for it and it lies outside every covered range. A key inside a covered range with no stored row is a known-empty key served as the empty default rather than a hole, and a key with a stored row is never reported as missing.

<sub>Verify level: **full** · Server-bound (`aristos:` namespace) · See [parent: eviction_preserves_holeness](./eviction_preserves_holeness.md)</sub>

---

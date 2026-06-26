**Aristo verified intent — `evicted_range_reverts_to_refillable_hole`**

Removing a key range discards its stored rows and its range coverage together as a unit, so every evicted key in the range reverts to a re-fillable hole reported as a miss by a later lookup — never left covered without rows and served as a known-empty result, and never left covered with stale rows.

<sub>Verify level: **full** · See [parent: partial_map_hole_versus_known_empty_discrimination](./partial_map_hole_versus_known_empty_discrimination.md)</sub>

---

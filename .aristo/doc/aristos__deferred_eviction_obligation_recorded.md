**Aristo verified intent — `aristos:deferred_eviction_obligation_recorded`**

An eviction received for a key whose buffered upquery response from the evicting ancestor is already held is retained as an outstanding eviction obligation on that buffered key. An obligation already outstanding for the key is left in force, and the eviction is neither discarded nor merged into the buffered records.

<sub>Verify level: **full** · Server-bound (`aristos:` namespace) · See [parent: eviction_debt_conserved](./eviction_debt_conserved.md)</sub>

---

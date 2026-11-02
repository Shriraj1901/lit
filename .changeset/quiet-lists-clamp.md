---
'@lit-labs/virtualizer': patch
---

Fix the `virtualize()` directive passing `undefined` to `keyFunction` and `renderItem` when `items` is replaced by a shorter array.

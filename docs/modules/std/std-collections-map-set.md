_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Map<K,V>](../../modules/std/std-collections-map.md).Set_
##### Method Set:[Bool](../../modules/wonkey/wonkey-types-bool.md)( key:K,value:V )
Sets the value associated with a key in the map.

If the map does not contain `key`, a new key/value node is added to the map and true is returned.

If the map already contains `key`, its associated value is updated and false is returned.

| Parameters |    |
|:-----------|:---|
| `key` | key The key. |
| `value` | value The value. |

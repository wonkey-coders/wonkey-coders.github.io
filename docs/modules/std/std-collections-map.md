_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).Map<K,V>_
##### Class Map<K,V>
The Map class provides support for associative maps.

A map is a container style object that provides a mechanism for associating 'key' objects with 'value' objects.
This is done using an internal node object that contains a reference to both a key and a value, along with information about the node'
s location within the map.

Each key in a map occurs exactly once - a map cannot contain multiple equivalent keys.

Maps can handle inserting, removing and finding keys in 'O(log2)' time. That is, the time needed to insert, remove or find a key is proportional to log2 of the number of items in the map.

| Structs | |
|:---|:---|
| [Iterator](std-collections-map<k?,v?>-iterator.md) |  |
| [KeyIterator](std-collections-map<k?,v?>-keyiterator.md) |  |
| [MapKeys](std-collections-map<k?,v?>-mapkeys.md) |  |
| [MapValues](std-collections-map<k?,v?>-mapvalues.md) |  |
| [ValueIterator](std-collections-map<k?,v?>-valueiterator.md) |  |

| Classes | |
|:---|:---|
| [Node](std-collections-map<k?,v?>-node.md) | The map Node class. |

| Constructors | |
|:---|:---|
| [New](std-collections-map<k?,v?>-new.md) | Creates a new empty map. |

| Properties | |
|:---|:---|
| [Empty](std-collections-map<k?,v?>-empty.md) | Checks if the map is empty. _(read only)_ |
| [Keys](std-collections-map<k?,v?>-keys.md) | Gets a view of the map's keys. _(read only)_ |
| [Values](std-collections-map<k?,v?>-values.md) | Gets a view of the map's values. _(read only)_ |

| Methods | |
|:---|:---|
| [Add](std-collections-map<k?,v?>-add.md) | Adds a new key/value pair to a map. |
| [All](std-collections-map<k?,v?>-all.md) | Gets a node iterator. |
| [Clear](std-collections-map<k?,v?>-clear.md) | Removes all keys from the map. |
| [Contains](std-collections-map<k?,v?>-contains.md) | Checks if the map contains a given key. |
| [Copy](std-collections-map<k?,v?>-copy.md) |  |
| [Count](std-collections-map<k?,v?>-count.md) | Gets the number of keys in the map. |
| [Get](std-collections-map<k?,v?>-get.md) | Gets the value associated with a key in the map. |
| [Remove](std-collections-map<k?,v?>-remove.md) | Removes a key from the map. |
| [Set](std-collections-map<k?,v?>-set.md) | Sets the value associated with a key in the map. |
| [Update](std-collections-map<k?,v?>-update.md) | Updates the value associated with a key in the map. |
| [Operator []](std-collections-map<k?,v?>-opidx.md) | Gets the value associated with a key in the map. |
| [Operator []=](std-collections-map<k?,v?>-opidxeq.md) | Sets the value associated with a key in the map. |

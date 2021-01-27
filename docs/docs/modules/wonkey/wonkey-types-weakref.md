_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).WeakRef_
##### Class WeakRef
Weak reference class.

A weak reference is an object that contains a reference to another object, but without preventing the other object from being garbage collected.

The [Target](wonkey-types-target.md) property returns the object being referenced, or null if the object has been garbage collected.

A weak reference must be contructed with the object it references.

| Constructors | |
|:---|:---|
| [New](wonkey-types-weakref-new.md) |  |

| Properties | |
|:---|:---|
| [Target](wonkey-types-weakref-target.md) |  _(read only)_ |

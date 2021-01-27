_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[List<T>](../../modules/std/std-collections-list.md).[BackwardsIterator](../../modules/std/std-collections-list-backwardsiterator.md).Erase_
##### Method Erase:Void(  )
Safely erases the node referenced by the iterator.

After calling this method, the iterator will point to the node after the removed node.

Therefore, if you are manually iterating through a list you should not call [Bump](std-collections-list-backwardsiterator-bump.md) after calling this method or you
will end up skipping a node.

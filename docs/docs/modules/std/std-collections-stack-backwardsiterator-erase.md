_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).[BackwardsIterator](../../modules/std/std-collections-stack-backwardsiterator.md).Erase_
##### Method Erase:Void(  )
Safely erases the value pointed to by the iterator.

After calling this method, the iterator will point to the value after the removed value.

Therefore, if you are manually iterating through a stack you should not call [Bump](std-collections-stack-backwardsiterator-bump.md) after calling this method or you
will end up skipping a value.

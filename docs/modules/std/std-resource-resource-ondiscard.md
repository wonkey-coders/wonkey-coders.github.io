_[std](../../modules/std/std-module.md):[std.resource](../../modules/std/std-resource.md).[Resource](../../modules/std/std-resource-resource.md).OnDiscard_
##### Method OnDiscard:Void(  )
The OnDiscard method.

This is where subclasses should place their actual discard code.

This method will be invoked the first time Resource.Discard() is invoked.

This method will only ever be invoked at most once during the lifetime of a resource.

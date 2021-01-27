_[std](../../modules/std/std-module.md):[std.resource](../../modules/std/std-resource.md).[Resource](../../modules/std/std-resource-resource.md).Discard_
##### Method Discard:Void(  )
Discards the resource.

If the resource has not yet been discarded, calling this method will cause any internally managed OS resources to be cleaned up.

If the resource has already been discarded, this method does nothing.

Once discarded, a resource should be consider invalid.

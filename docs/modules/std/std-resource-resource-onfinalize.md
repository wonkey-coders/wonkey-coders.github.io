_[std](../../modules/std/std-module.md):[std.resource](../../modules/std/std-resource.md).[Resource](../../modules/std/std-resource-resource.md).OnFinalize_
##### Method OnFinalize:Void(  )
The OnFinalize method.

This method will be invoked when a resource object's memory is about to be reclaimed and if the resource's Discard() method has
never been called during the lifetime of the object.

This method is intended to be used for the 'last chance' cleanup of criticial OS resources, such as file handles, texture objects etc.

***** WARNING *****

Code inside this method executes at a critical point in the garbage collection process, and should be kept short and sweet.

Code inside OnFinalize MUST obey the following rules:

* Code MUST NOT read or write any fields of Self containing objects, arrays, or function pointers as there is no guarantee that such fields
are still valid when the finalizer executes.

* Code MUST NOT assign Self to any variable.

Failure to follow these rules *will* lead to eventual disaster!

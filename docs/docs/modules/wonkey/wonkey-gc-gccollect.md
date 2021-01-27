_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.gc](../../modules/wonkey/wonkey-gc.md).GCCollect_
##### Function GCCollect:Void(  )
Performs a garbage collection.

Marks all unused memory as 'garbage' and makes it available for reuse in the future.

You should not generally need to use this method as garbage collection is performed automatically.

However, it can be useful when debugging a program for memory leaks to force a garbage collection to run.

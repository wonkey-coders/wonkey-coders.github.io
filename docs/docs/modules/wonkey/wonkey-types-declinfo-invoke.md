_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[DeclInfo](../../modules/wonkey/wonkey-types-declinfo.md).Invoke_
##### Method Invoke:[Variant](../../modules/wonkey/wonkey-types-variant.md)( instance:[Variant](../../modules/wonkey/wonkey-types-variant.md),params:[Variant](../../modules/wonkey/wonkey-types-variant.md)[] )
Invokes method or function.

If the declaration kind is 'Function', the `instance` parameter is ignored.

A runtime error will occur if the declaration kind is not 'Method' or 'Function'.

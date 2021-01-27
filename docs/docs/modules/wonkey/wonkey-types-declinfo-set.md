_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[DeclInfo](../../modules/wonkey/wonkey-types-declinfo.md).Set_
##### Method Set:Void( instance:[Variant](../../modules/wonkey/wonkey-types-variant.md),value:[Variant](../../modules/wonkey/wonkey-types-variant.md) )
Sets field, property or global value.

If the declaration kind is 'Global', the `instance` parameter is ignored.

A runtime error will occur if the declaration kind is not 'Field' or 'Global'.

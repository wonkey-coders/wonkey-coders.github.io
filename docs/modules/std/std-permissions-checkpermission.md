_[std](../../modules/std/std-module.md):[std.permissions](../../modules/std/std-permissions.md).CheckPermission_
##### Function CheckPermission:[Int](../../modules/wonkey/wonkey-types-int.md)( permission:[String](../../modules/wonkey/wonkey-types-string.md) )
Check an android permission.

This function is only available on android.

Returns 1 if the given permission has been granted to the app, else 0.

The permission string should be in android manifest form, eg: "android.permission.READ\_EXTERNAL\_STORAGE".

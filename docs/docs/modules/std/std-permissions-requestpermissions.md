_[std](../../modules/std/std-module.md):[std.permissions](../../modules/std/std-permissions.md).RequestPermissions_
##### Function RequestPermissions:Void( permissions:[String](../../modules/wonkey/wonkey-types-string.md)[],finished:Void([ResultType](../../modules/std/std-permissions-resulttype.md)[]) )
Request android permissions.

This function is only available on android.

Attempts to grant the given permissions to the app.

Depending on the permissions, this may cause a modal dialog to be presented to the user.

The permission strings should be in android manifest form, eg: "android.permission.READ\_EXTERNAL\_STORAGE".

See this page for more permissions:

https://developer.android.com/reference/android/Manifest.permission

If the result is an empty array, the operation was cancelled.

_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).ExternalDir_
##### Function ExternalDir:[String](../../modules/wonkey/wonkey-types-string.md)(  )
Gets the filesystem directory of the app's external storage directory.

Returns the absolute path to the directory on the primary shared/external storage device where the application can place persistent files it owns. These files are internal to the applications, and not typically visible to the user as media.

This directory will be removed when your app is uninstalled.

This function is only available on mobile targets.

_[std](../../modules/std/std-module.md):[std.requesters](../../modules/std/std-requesters.md).RequestFile_
##### Function RequestFile:[String](../../modules/wonkey/wonkey-types-string.md)( title:[String](../../modules/wonkey/wonkey-types-string.md),filter:[String](../../modules/wonkey/wonkey-types-string.md)="",save:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false,file:[String](../../modules/wonkey/wonkey-types-string.md)="" )
Activates a modal file requester dialog.

RequestFile activates a modal file requester dialog.

The optional filters string can either be a comma separated list of file extensions or, as in the following example, groups of extensions that begin with a "group:" label and are separated by a semicolon. For example:

"Image files:png,jpg;Audio files:was,ogg;All files:*"

The save parameter should be true to create a save-style requester, false to create a load-style requester.

The `path` parameter can be used to specify an initial file path.

Returns selected file path, or an empty string if dialog was cancelled.

_[mojox](../../modules/mojox/mojox-module.md):[mojox](../../modules/mojox/mojox-module.md).RequestOkay_
##### Function RequestOkay:[Bool](../../modules/wonkey/wonkey-types-bool.md)( message:[String](../../modules/wonkey/wonkey-types-string.md)="Are you sure you want to do this?",title:[String](../../modules/wonkey/wonkey-types-string.md)="Okay?",yesButton:[String](../../modules/wonkey/wonkey-types-string.md)="Okay",noButton:[String](../../modules/wonkey/wonkey-types-string.md)="Cancel" )
Runs a simple 'okay/cancel' dialog.

Returns true if the user selects 'Okay', else false.

This function must not be called from the main fiber.

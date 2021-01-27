_[std](../../modules/std/std-module.md):[std.resource](../../modules/std/std-resource.md).Resource_
##### Class Resource
The Resource class.

The resource class helps with managing finite OS resources in a garbage collected environment.

To implement a resource object, you should extend the Resource class and override the [OnDiscard](std-resource-ondiscard.md) and/or [OnFinalize](std-resource-onfinalize.md) methods.

Code to actually discard the resource should be placed in OnDiscard. Discarding a resource might involve closing a file, deleting
a texture handle or other similar actions. 'Last chance' cleanup code should be placed in OnFinalize.

IMPORTANT! There are a number of restrictions on code that may be placed in OnFinalize, please refer to the documentation for [OnFinalize](std-resource-onfinalize.md)
for more information.

| Methods | |
|:---|:---|
| [Discard](std-resource-resource-discard.md) | Discards the resource. |

| Protected methods | |
|:---|:---|
| [OnDiscard](std-resource-resource-ondiscard.md) | The OnDiscard method. |
| [OnFinalize](std-resource-resource-onfinalize.md) | The OnFinalize method. |

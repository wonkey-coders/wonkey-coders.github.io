_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.debug](../../modules/wonkey/wonkey-debug.md).DebugAssert_
##### Function DebugAssert:Void( condition:[Bool](../../modules/wonkey/wonkey-types-bool.md),message:[String](../../modules/wonkey/wonkey-types-string.md)="Debug assert failed" )
Generates a runtime error if a boolean expression is false (debug builds only).

This function does not execute at all in release builds, so make sure that `condition` doesn't inadvertantly execute
any critical code.

| Parameters |    |
|:-----------|:---|
| `condition` | condition The boolean condition to check. |
| `message` | message Runtime error message to generate. |

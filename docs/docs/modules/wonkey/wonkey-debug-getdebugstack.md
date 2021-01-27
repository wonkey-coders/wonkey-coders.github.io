_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.debug](../../modules/wonkey/wonkey-debug.md).GetDebugStack_
##### Function GetDebugStack:[String](../../modules/wonkey/wonkey-types-string.md)[](  )
Gets the current stack state (debug builds only).

In release mode, an empty array is returned.

```
Namespace test

Function Test2()
	Print "~n".Join( GetDebugStack() )
End

Function Test()
	Test2()
End

Function Main()
	Test()
End
```

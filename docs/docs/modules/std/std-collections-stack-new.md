_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[Stack<T>](../../modules/std/std-collections-stack.md).New_
##### Method New:Void(  )
##### Method New:Void( length:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method New:Void( values:T[] )
##### Method New:Void( values:[List](../../modules/std/std-collections-list.md)<T> )
##### Method New:Void( values:[Deque](../../modules/std/std-collections-deque.md)<T> )
##### Method New:Void( values:[Stack](../../modules/std/std-collections-stack.md)<T> )
Creates a new stack.

New() creates an empty stack.

New( length:Int ) creates a stack that initially contains `length` null values.

New( values:T[] ) creates a stack with the contents of an array.

New( values:List<T> ) creates a stack with the contents of a list.

New( values:Deque<T> ) create a stack with the contents of a deque.

New( values:Stack<T> ) create a stack with the contents of another stack.

| Parameters |    |
|:-----------|:---|
| `length` | length The length of the stack. |
| `values` | values An array, list or stack. |

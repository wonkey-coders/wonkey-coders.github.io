_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).[List<T>](../../modules/std/std-collections-list.md).[Node](../../modules/std/std-collections-list-node.md).New_
##### Method New:Void( value:T )
##### Method New:Void( value:T,succ:[List](../../modules/std/std-collections-list.md)<T>.[Node](../../modules/std/std-collections-list-node.md) )
Creates a new node not in any list.
Creates a new node with the given successor node.

Warning! No error checking is performed!

This method should not be used while iterating over the list containing `succ`.

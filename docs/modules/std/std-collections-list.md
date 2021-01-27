_[std](../../modules/std/std-module.md):[std.collections](../../modules/std/std-collections.md).List<T>_
##### Class List<T> Implements [IContainer](../../modules/std/std-collections-icontainer.md)<T>
The List class provides support for linked lists.

A linked list is a container style data structure that provides efficient support for the addition, removal and sequential traversal of objects.

A linked list works by connecting elements together with 'next' and 'previous' references, making it very efficient to get from one element to the next, but not so efficient for accessing arbitrary elements.

This connection between elements is achieved using separate Node objects (there is one per element) which contain references to the next and previous nodes in the list, as well as the actual object managed by the node.

Lists implements the [IContainer](std-collections-icontainer.md) interface so can be used with Eachin loops.

| Structs | |
|:---|:---|
| [BackwardsIterator](std-collections-list<t?>-backwardsiterator.md) | The List.BackwardsIterator struct. |
| [Iterator](std-collections-list<t?>-iterator.md) | The List.Iterator struct. |

| Classes | |
|:---|:---|
| [Node](std-collections-list<t?>-node.md) | The List.Node class. |

| Constructors | |
|:---|:---|
| [New](std-collections-list<t?>-new.md) | Creates a new list. |

| Properties | |
|:---|:---|
| [Empty](std-collections-list<t?>-empty.md) | Checks whether the list is empty. _(read only)_ |
| [First](std-collections-list<t?>-first.md) | Gets the first value in the list. _(read only)_ |
| [Last](std-collections-list<t?>-last.md) | Gets the last value in the list _(read only)_ |

| Methods | |
|:---|:---|
| [Add](std-collections-list<t?>-add.md) | Adds a value to the end of the list. |
| [AddAll](std-collections-list<t?>-addall.md) | Adds all values in an array or container to the end of the list. |
| [AddFirst](std-collections-list<t?>-addfirst.md) | Adds a value to the start of the list. |
| [AddLast](std-collections-list<t?>-addlast.md) | Adds a value to the end of the list. |
| [All](std-collections-list<t?>-all.md) | Gets an iterator for visiting list values. |
| [Backwards](std-collections-list<t?>-backwards.md) | Gets an iterator for visiting list values in reverse order. |
| [Clear](std-collections-list<t?>-clear.md) | Removes all values from the list. |
| [Count](std-collections-list<t?>-count.md) | Counts the number of values in the list. |
| [FindLastNode](std-collections-list<t?>-findlastnode.md) | Finds the last node in the list containing a value. |
| [FindNode](std-collections-list<t?>-findnode.md) | Finds the first node in the list containing a value. |
| [FirstNode](std-collections-list<t?>-firstnode.md) | Gets the first node in the list. |
| [HeadNode](std-collections-list<t?>-headnode.md) | Gets the head node of the list. |
| [Join](std-collections-list<t?>-join.md) | Joins the values in the string list. |
| [LastNode](std-collections-list<t?>-lastnode.md) | Gets the last node in the list. |
| [Remove](std-collections-list<t?>-remove.md) | Removes the first value in the list equal to a given value. |
| [RemoveEach](std-collections-list<t?>-removeeach.md) | Removes all values in the list equal to a given value. |
| [RemoveFirst](std-collections-list<t?>-removefirst.md) | Removes and returns the first value in the list. |
| [RemoveIf](std-collections-list<t?>-removeif.md) | Removes all values in the list that fulfill a condition. |
| [RemoveLast](std-collections-list<t?>-removelast.md) | Removes the last value in the list equal to a given value. |
| [Sort](std-collections-list<t?>-sort.md) | Sorts the list. |
| [ToArray](std-collections-list<t?>-toarray.md) | Converts the list to an array. |

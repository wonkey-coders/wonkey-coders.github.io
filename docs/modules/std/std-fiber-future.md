_[std](../../modules/std/std-module.md):[std.fiber](../../modules/std/std-fiber.md).Future<T>_
##### Class Future<T>
Futures provide support for simple fiber synchronization.

A future allows you to synchronize two fibers by providing a way for one fiber to signal to another that an operation has completed.

The general usage pattern of futures is:

* Fiber A creates a future and passes it to fiber B.

* Fiber A then calls [Get](std-fiber-get.md) on the future. This will suspend Fiber A.

* Fiber B performs some operation, then calls [Set](std-fiber-set.md) on the future. This will resume Fiber A.

A future can only be set once.

| Constructors | |
|:---|:---|
| [New](std-fiber-future<t?>-new.md) | Creates a new future. |

| Methods | |
|:---|:---|
| [Get](std-fiber-future<t?>-get.md) | Gets the future's value. |
| [Set](std-fiber-future<t?>-set.md) | Sets the future's value. |

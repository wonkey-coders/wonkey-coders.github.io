_[std](../../modules/std/std-module.md):[std.fiber](../../modules/std/std-fiber.md).Fiber_
##### Struct Fiber
Fibers provide support for asynchronous programming.

A Fiber is a lightweight 'thread of execution' that can be used to achieve a form of cooperative multitasking.

A fiber can be in one of 4 states:

* Running. There is only ever one fiber in the running state at a time. This is the fiber returned by [Fiber.Current](std-fiber-fiber.current.md).

* Suspended. A fiber is in the suspended state if it has called [Fiber.Suspend](std-fiber-fiber.suspend.md). A suspended fiber can only be returned to the running state by some other fiber calling [Resume](std-fiber-resume.md) on it.

* Paused. A fiber is in the paused state after it has called [Resume](std-fiber-resume.md) on another fiber and that fiber has resumed running. A paused fiber will continue running when the fiber it resumed calls [Suspend](std-fiber-suspend.md) or exits normally.

* Terminated. The fiber has either returned from i's entry function, or has been explicitly terminated via a call to [Terminate](std-fiber-terminate.md).

| Constructors | |
|:---|:---|
| [New](std-fiber-fiber-new.md) | Creates a new fiber. |

| Properties | |
|:---|:---|
| [Debug](std-fiber-fiber-debug.md) |  _(read only)_ |

| Methods | |
|:---|:---|
| [Resume](std-fiber-fiber-resume.md) | Resumes a suspended fiber. |
| [Terminate](std-fiber-fiber-terminate.md) | Terminates a fiber. |

| Functions | |
|:---|:---|
| [CreateSuspended](std-fiber-fiber-createsuspended.md) |  - not really needed? |
| [Current](std-fiber-fiber-current.md) | Gets the currently running fiber. |
| [Main](std-fiber-fiber-main.md) | Gets the main fiber. |
| [Sleep](std-fiber-fiber-sleep.md) | Puts current fiber to sleep. |
| [Suspend](std-fiber-fiber-suspend.md) | Suspends the current fiber. |

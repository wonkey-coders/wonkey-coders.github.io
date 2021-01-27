_[mojox](../../modules/mojox/mojox-module.md):[mojox](../../modules/mojox/mojox-module.md).[Action](../../modules/mojox/mojox-action.md).Async_
##### Property Async:[Bool](../../modules/wonkey/wonkey-types-bool.md)
Action async flag.

If true (the default), then when the action is triggered the [Triggered](mojox-action-triggered.md) signal is run on a new fiber.

Note: Fiber are not supported in emscripten, so this property has no effect.

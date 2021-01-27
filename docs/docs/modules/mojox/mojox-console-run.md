_[mojox](../../modules/mojox/mojox-module.md):[mojox](../../modules/mojox/mojox-module.md).[Console](../../modules/mojox/mojox-console.md).Run_
##### Method Run:[Bool](../../modules/wonkey/wonkey-types-bool.md)( cmd:[String](../../modules/wonkey/wonkey-types-string.md) )
Runs a process.

Returns true if the process was successfully started, else false.

Process stdout is written to the console while the process is running.

This method waits for the process to complete, so should always be called on a fiber.

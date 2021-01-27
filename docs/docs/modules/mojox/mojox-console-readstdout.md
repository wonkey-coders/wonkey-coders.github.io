_[mojox](../../modules/mojox/mojox-module.md):[mojox](../../modules/mojox/mojox-module.md).[Console](../../modules/mojox/mojox-console.md).ReadStdout_
##### Method ReadStdout:[String](../../modules/wonkey/wonkey-types-string.md)(  )
Reads process stdout.

If an empty string is returned, the process has finished.

This method may have to wait for stdout to become available, so should always be called on a fiber.

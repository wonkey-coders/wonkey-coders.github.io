_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Model](../../modules/mojo3d/mojo3d-model.md).LoadBoned_
##### Function LoadBoned:[Model](../../modules/mojo3d/mojo3d-model.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Loads a boned model from a file path.

On its own, mojo3d can only load gltf2 format mesh and model files.

To add more formats, #import the mojo3d-assimp module into your app, eg:

```
```

This will allow you to load any format supported by the assimp module.

However, importing the assimp module into your app will also increase its size.

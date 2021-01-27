_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Entity](../../modules/mojo3d/mojo3d-entity.md).CopyTo_
##### Method CopyTo:Void( copy:[Entity](../../modules/mojo3d/mojo3d-entity.md) )
Helper method for copying an entity.

1) Recursively copies all child entities.

2) Invokes OnCopy for each component attached to this entity.

3) Copies visibility.

4) Invokes Copied signal.

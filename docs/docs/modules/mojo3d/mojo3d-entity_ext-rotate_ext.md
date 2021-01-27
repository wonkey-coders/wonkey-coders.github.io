_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Entity](../../modules/mojo3d/mojo3d-entity_ext.md).Rotate_
##### Method Rotate:Void( rv:[std.geom.Vec3f](../../modules/std/std-geom-vec3f.md),localSpace:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
##### Method Rotate:Void( rx:[Float](../../modules/wonkey/wonkey-types-float.md),ry:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),localSpace:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Rotates the entity.

Rotates the entity.

If `localSpace` is false, the rotation is applied after the entity's world rotation.

If `localSpace` is true, the rotation is applied before the entity's local rotation.

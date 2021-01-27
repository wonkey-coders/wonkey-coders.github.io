_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Mesh](../../modules/mojo3d/mojo3d-mesh.md).New_
##### Method New:Void(  )
##### Method New:Void( vertices:[mojo.graphics.Vertex3f](../../modules/mojo/mojo-graphics-vertex3f.md)[],indices:[UInt](../../modules/wonkey/wonkey-types-uint.md)[] )
Creates a new mesh.

Creates a new empty mesh.

Meshes don't actual contain instances of materials. Instead, mesh triangles are added to 'logical' materials which are effectively just integer indices.

Actual materials are stored in models, and can be accessed via the [Model.Materials](mojo3d-mesh-model.materials.md) property.

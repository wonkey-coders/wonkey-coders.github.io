_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Mesh](../../modules/mojo3d/mojo3d-mesh.md).AddTriangles_
##### Method AddTriangles:Void( indices:[UInt](../../modules/wonkey/wonkey-types-uint.md) Ptr,count:[Int](../../modules/wonkey/wonkey-types-int.md),materialid:[Int](../../modules/wonkey/wonkey-types-int.md)=0 )
##### Method AddTriangles:Void( indices:[UInt](../../modules/wonkey/wonkey-types-uint.md)[],materialid:[Int](../../modules/wonkey/wonkey-types-int.md)=0 )
Adds triangles to the mesh.

`count` is the number of indices to add and must be a multiple of 3.

`materialid` must be a valid material id in the range 0 to [NumMaterials](mojo3d-mesh-nummaterials.md) inclusive.

If `materialid` is equal to NumMaterials, a new material is automatically added first.

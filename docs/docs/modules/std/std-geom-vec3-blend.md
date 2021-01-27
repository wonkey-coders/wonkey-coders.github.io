_[std](../../modules/std/std-module.md):[std.geom](../../modules/std/std-geom.md).[Vec3<T>](../../modules/std/std-geom-vec3.md).Blend_
##### Method Blend:[Vec3](../../modules/std/std-geom-vec3.md)<T>( v:[Vec3](../../modules/std/std-geom-vec3.md)<T>,alpha:[Double](../../modules/wonkey/wonkey-types-double.md) )
Blends the vec3 with another vec3.

Components are linearly blended using `alpha` as a weighting factor.

If alpha is 0, self is returned.

If alpha is 1, `v` is returned.

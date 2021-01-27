_[std](../../modules/std/std-module.md):[std.geom](../../modules/std/std-geom.md).AffineMat4<T>_
##### Struct AffineMat4<T>
The generic AffineMat4f class provides support for affine 4x4 matrices.

An affine 4x4 matrix is a 4x4 matrix whose right hand column is always 0,0,0,1.

Affine 4x4 matrices are often used for 3d transformations such as scaling, rotation and translation.

Unless otherwise noted, methods and operators always return a new vec3 containing the result, without modifying any parameters or 'self'.

This allows you to chain operators together easily just like 'real' expressions.

| Fields | |
|:---|:---|
| [m](std-geom-affinemat4<t?>-m.md) | The matrix component of the matrix. |
| [t](std-geom-affinemat4<t?>-t.md) | The translation component of the matrix. |

| Constructors | |
|:---|:---|
| [New](std-geom-affinemat4<t?>-new.md) | Creates a new matrix. |

| Methods | |
|:---|:---|
| [Operator *](std-geom-affinemat4<t?>-opmul.md) | Multiplies the matrix by another matrix. |
| [Operator -](std-geom-affinemat4<t?>-opsub.md) | Inverts the matrix. |
| [Rotate](std-geom-affinemat4<t?>-rotate.md) | Applies a rotation transformation to the matrix. |
| [Scale](std-geom-affinemat4<t?>-scale.md) | Applies a scaling transformation to the matrix. |
| [Translate](std-geom-affinemat4<t?>-translate.md) | Applies a translation transformation to the matrix. |
| [Operator To](std-geom-affinemat4<t?>-to.md) | Converts the matrix to a matrix of a different type, or a printable string. |
| [Operator ~](std-geom-affinemat4<t?>-opxor.md) | Transposes the matrix. |

| Functions | |
|:---|:---|
| [Rotation](std-geom-affinemat4<t?>-rotation.md) | Creates a matrix repsenting a rotation form eular angles or a quat. |
| [Scaling](std-geom-affinemat4<t?>-scaling.md) | Creates a matrix representing a scaling. |
| [Translation](std-geom-affinemat4<t?>-translation.md) | Creates a matrix representing a translation. |

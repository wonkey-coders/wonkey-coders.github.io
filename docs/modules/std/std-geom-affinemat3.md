_[std](../../modules/std/std-module.md):[std.geom](../../modules/std/std-geom.md).AffineMat3<T>_
##### Struct AffineMat3<T>
The generic AffineMat3f class provides support for affine 3x3 matrices.

An affine 3x3 matrix is a 3x3 matrix whose right hand column is always 0,0,1.

Affine 3x3 matrices are often used for 2d transformations such as scaling, rotation and translation.

Unless otherwise noted, methods and operators always return a new vec3 containing the result, without modifying any parameters or 'self'.

This allows you to chain operators together easily just like 'real' expressions.

| Fields | |
|:---|:---|
| [i](std-geom-affinemat3<t?>-i.md) | The first row of the matrix. |
| [j](std-geom-affinemat3<t?>-j.md) | The second row of the matrix. |
| [t](std-geom-affinemat3<t?>-t.md) | The third row of the matrix. |

| Constructors | |
|:---|:---|
| [New](std-geom-affinemat3<t?>-new.md) | Creates a new matrix. |

| Methods | |
|:---|:---|
| [Operator *](std-geom-affinemat3<t?>-opmul.md) | Multiplies a vector by the matrix. |
| [Operator -](std-geom-affinemat3<t?>-opsub.md) | Inverts the matrix. |
| [Rotate](std-geom-affinemat3<t?>-rotate.md) | Applies a rotation transformation to the matrix. |
| [Scale](std-geom-affinemat3<t?>-scale.md) | Applies a scale transformation to the matrix. |
| [Transform](std-geom-affinemat3<t?>-transform.md) | Multiplies a vector by the matrix. |
| [Translate](std-geom-affinemat3<t?>-translate.md) | Applies a translation transformation to the matrix. |
| [Operator To](std-geom-affinemat3<t?>-to.md) | Converts the matrix to a matrix of a different type, or a printable string. |

| Functions | |
|:---|:---|
| [Ortho](std-geom-affinemat3<t?>-ortho.md) | Creates a matrix representing an orthographic projection. |
| [Rotation](std-geom-affinemat3<t?>-rotation.md) | Creates a matrix representing a rotation. |
| [Scaling](std-geom-affinemat3<t?>-scaling.md) | Creates a matrix representing a scaling. |
| [Translation](std-geom-affinemat3<t?>-translation.md) | Creates a matrix representing a translation. |

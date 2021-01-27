_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).Entity_
##### Class Entity Abstract
The Entity class.

| Fields | |
|:---|:---|
| [Copied](mojo3d-entity-copied.md) | Copied signal. |
| [Destroyed](mojo3d-entity-destroyed.md) | Destroyed signal. |
| [Hidden](mojo3d-entity-hidden.md) | Hidden signal. |
| [Shown](mojo3d-entity-shown.md) | Shown signal. |

| Constructors | |
|:---|:---|
| [New](mojo3d-entity-new.md) | Creates a new entity. |

| Properties | |
|:---|:---|
| [Alpha](mojo3d-entity-alpha.md) | Master alpha. |
| [Basis](mojo3d-entity-basis.md) | World space basis matrix. |
| [Children](mojo3d-entity-children.md) | Array of child entities. _(read only)_ |
| [Color](mojo3d-entity-color.md) | Master color. |
| [Components](mojo3d-entity-components.md) | Array of attached components. _(read only)_ |
| [InverseMatrix](mojo3d-entity-inversematrix.md) | Inverse world space transformation matrix. _(read only)_ |
| [LastCopy](mojo3d-entity-lastcopy.md) | Last copy. _(read only)_ |
| [LocalBasis](mojo3d-entity-localbasis.md) | Local space basis matrix. |
| [LocalMatrix](mojo3d-entity-localmatrix.md) | Local space transformation matrix. |
| [LocalPosition](mojo3d-entity-localposition.md) | Local space position. |
| [LocalScale](mojo3d-entity-localscale.md) | Local space scale. |
| [Matrix](mojo3d-entity-matrix.md) | World space transformation matrix. |
| [Name](mojo3d-entity-name.md) | Name |
| [NumChildren](mojo3d-entity-numchildren.md) | Number of child entities. _(read only)_ |
| [Parent](mojo3d-entity-parent.md) | Parent entity. |
| [Position](mojo3d-entity-position.md) | World space position. |
| [ReallyVisible](mojo3d-entity-reallyvisible.md) | True if entity and all parents are visible. _(read only)_ |
| [Scale](mojo3d-entity-scale.md) | World space scale. |
| [Scene](mojo3d-entity-scene.md) | Scene _(read only)_ |
| [Seq](mojo3d-entity-seq.md) | Sequence id _(read only)_ |
| [Visible](mojo3d-entity-visible.md) | Visibility flag. |

| Methods | |
|:---|:---|
| [AddComponent](mojo3d-entity-addcomponent.md) | Attaches a component to the entity. |
| [Copy](mojo3d-entity-copy.md) | Creates a copy of the entity. |
| [Destroy](mojo3d-entity-destroy.md) | Destroys the entity and all of its children. |
| [Find](mojo3d-entity-find.md) | Finds an entity with the given name. |
| [GetComponent](mojo3d-entity-getcomponent.md) | Gets a component of a given type attached to the entity. |
| [GetComponents](mojo3d-entity-getcomponents.md) |  |
| [NumComponents](mojo3d-entity-numcomponents.md) | Gets the number of components of a given type attached to the entity. |

| Protected methods | |
|:---|:---|
| [CopyTo](mojo3d-entity-copyto.md) | Helper method for copying an entity. |
| [OnHide](mojo3d-entity-onhide.md) | Invoked when entity transitions from visible->hidden. |
| [OnShow](mojo3d-entity-onshow.md) | Invoked when entity transitions from hidden->visible. |

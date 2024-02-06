---
share: true
---


Definition:: A 2d surface

$v=v_0+t_1v_1+t_2v_2$

## Usefull ~~Functions~~ Equations
### Distance between a point and a plane
$$D=\frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}$$
where $P_0(x_0, y_0, z_0)$ is the point
and $ax+by+cz+d$ is the plane

## Representations
### Points and Normals
A plane can be represented by a point on the plane and a [Normal](Normal.md) representing it's direction.
It's equation is $n\cdot \overrightarrow{P_0P}$, which when expanded to 3d looks like
$$a(x_0-x)+b(y_0-y)+c(z_0-z)$$

### 2 Noncollinear Vectors 
A plane can be represented by 2 vectors that are parallel to the plane.
Where the [Normal](Normal.md) can be found by the dot product of the 2 vectors 

### Three Points
A plane can also be represented with 3 points on the plane, this will form a triangle face that is parallel to the plane, counting the [Normal](Normal.md) is simply the dot product of 2 vectors in the plane.


---
Related:
- [Example](../../Example.md) : An example note

Further Reading:
- [Example](../../Example.md)

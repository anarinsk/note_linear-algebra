

# Meaning of Projection

![](http://blogs.jccc.edu/rgrondahl/files/2012/02/perpendicularprojection.jpg)

$u \cdot v = \lVert \text{Proj}_v u \rVert \lVert v \rVert$

$\cos \theta$ is to be $\dfrac{\lVert \text{Proj}_v u \rVert}{\lVert u \rVert}$. 

Thus, 

$$
\cos \theta = \frac{u \cdot v}{\lVert u \rVert {\,}\lVert v \rVert}
$$

# Dot product with COS 

## How to proof 

[LINK](https://math.stackexchange.com/questions/116133/how-to-understand-dot-product-is-the-angles-cosine)

* [Law of COS](https://en.wikipedia.org/wiki/Law_of_cosines)

$$
\lVert a - b \rVert^2 = \lVert a \rVert^2 + \lVert  b \rVert^2 - 2\lVert a \rVert \lVert  b \rVert^2 \cos \theta
$$

* [bilinearity](https://en.wikipedia.org/wiki/Bilinear_map) and symmetry 

$$
\lVert a - b \rVert^2 = \langle a-b, a-b \rangle = \lVert a \rVert^2 +  \lVert b \rVert^2 - 2\langle a, b \rangle 
$$

Thus, 

$$
\langle a, b \rangle = \lvert\lvert a \rvert\rvert  {\,} \lvert\lvert b \rvert\rvert \cos \theta 
$$

Geometrically, dot product is multiplication of the length of vector projected and the one projecting. 

# Cauchy-Schwarz Inequality 

## Statement 

$$
\rvert \langle u, v \rangle \lvert^2 \leq \langle v, v \rangle \langle u,u \rangle
$$ 

## Proof 

$$
\rvert \langle u, v \rangle \lvert \leq \lVert v \rVert \lVert u \rVert
$$ 

if $v=0$, equality holds. 

Let 

$$
z = u - u_v = u - \frac{\langle u,v \rangle}{\langle v,v \rangle} v
$$

$$
\langle z, v \rangle = 0
$$

$$
\lVert u \rVert^2 = \lvert \dfrac{\langle u,v \rangle}{\langle v, v \rangle} \rvert^2 \lVert v \rVert^2 + 
$$




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDE1NTQ3NzEsNjg1MDI1NDU2LDkzNj
cyODgyLC0xNzM5MzIxMTczLC0yMDUzMDY4MTY3LDU2MTUxNzcz
MSwtMTc3NTU2Mzk2Ml19
-->
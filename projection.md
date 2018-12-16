

# Meaning of Projection

![](http://blogs.jccc.edu/rgrondahl/files/2012/02/perpendicularprojection.jpg)

$u \cdot v = \lVert \text{Proj}_v u \rVert \lVert\lvert v \rvert\rvert$

$\cos \theta$ is to be $\dfrac{\lvert\lvert \text{Proj}_v u \rvert\rvert}{\lvert\lvert u \rvert\rvert}$. 

Thus, 

$$
\cos \theta = \frac{u \cdot v}{\lvert\lvert u \rvert\rvert {\,}\lvert\lvert v \rvert\rvert}
$$

# Dot product with COS 

## How to proof 

[LINK](https://math.stackexchange.com/questions/116133/how-to-understand-dot-product-is-the-angles-cosine)

* [Law of COS](https://en.wikipedia.org/wiki/Law_of_cosines)

$$
\lvert\lvert a - b \rvert\rvert^2 = \lvert\lvert a \rvert\rvert^2 + \lvert\lvert  b \rvert\rvert^2 - 2\lvert\lvert a \rvert\rvert \lvert\lvert  b \rvert\rvert^2 \cos \theta
$$

* [bilinearity](https://en.wikipedia.org/wiki/Bilinear_map) and symmetry 

$$
\lvert\lvert a - b \rvert\rvert^2 = \langle a-b, a-b \rangle = \lvert\lvert a \rvert\rvert^2 +  \lvert\lvert b \rvert\rvert^2 - 2\langle a, b \rangle 
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
\rvert \langle u, v \rangle \lvert \leq \lVert v \rangle \langle u,u \rangle
$$ 



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5ODUxMjM3NDUsNjg1MDI1NDU2LDkzNj
cyODgyLC0xNzM5MzIxMTczLC0yMDUzMDY4MTY3LDU2MTUxNzcz
MSwtMTc3NTU2Mzk2Ml19
-->
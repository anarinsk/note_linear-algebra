
# Understanding Gram-Schmidt process 

## Where / Source 

https://en.wikipedia.org/wiki/Gram%E2%80%93Schmidt_process

## Who 

## What 

 The **Gram–Schmidt process** is a method for [orthonormalising](https://en.wikipedia.org/wiki/Orthonormal_basis "Orthonormal basis") a set of [vectors](https://en.wikipedia.org/wiki/Vector_(geometry) "Vector (geometry)") in an [inner product space](https://en.wikipedia.org/wiki/Inner_product_space "Inner product space"), most commonly the [Euclidean space](https://en.wikipedia.org/wiki/Euclidean_space "Euclidean space")  $\mathbb R_n$ equipped with the [standard inner product](https://en.wikipedia.org/wiki/Standard_inner_product "Standard inner product").

* 한마디로 말하면 임의의 각도들로 배열된 벡터의 내적 공간을 직교 베이스 벡터들로 다시 위치를 잡아주는 과정이다. 
* 다시 말하면,  서로 직교하는 표준 기저로 원래 벡터들을 생성해내는 과정이다. 

## When / Cases of Application 

* 온갖 decomposition 과정에서 동원된다. 기본적인 내용이니 알아두도록 하자. 

## How 

### 2nd dimension 

* Set of original vectors is $\lbrace v_1, v_2, \dotsc, v_n \rbrace$, and Set of orthogonal bases is $\lbrace u_1, u_2, \dotsc, u_n \rbrace$

* Start with $v_1 = u_1$
* Let $\text{proj}_u (v)$ be project of $v$ to vector $u$. 
* For $\text{proj}_{u_1} (v_2)$, let put $u_2$ which is orthogonal to $u_1$
* $v_2$ can be constructed with $\text{proj}_{u_1} (v_2)$, $u_2$
* That is, $u_2$ is constructed by $u_2 = v_2 - \text{proj}_{u_1}(v_2)$

## Generalization to $k$-dimension 

$u_1 = v_1$

$u_2 = v_2 - \text{proj}_{u_1} (v_2)$

$u_3 = v_3$ $-$ $\text{proj}_{u_1} (v_3)$ $-$ $\mathrm{proj}_{u_2} (v_3)$

$\vdots$

$u_k = v_k -\sum_{j=1}^{k-1} \text{proj}_{u_j}(v_k)$

## Why / Why this is important 

* PCA 분석은 자료가 있을 때 이 자료를 적절한 축으로 돌려서 해당 축들에게 정보를 많이 파악하도록 만드는 것이다. 
* 이것이 Principal이라고 부르는 이유는 서로 orthogonal하기 때문이다. 즉, 축 간에 서로 코릴레이션이 없게 된다. 
	* 즉 해당 축들로 프로젝션된 대상들 사이에는 correlation이 없음으로 변수들 사이의 다중공선성 같은 걸 걱정할 필요가 없게 되는 것 
 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMzY1NDA3OTgsNjk3MDE4MzEyLDI5OT
g3MzM2XX0=
-->
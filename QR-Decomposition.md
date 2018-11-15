
# QR Decomposition 

## Who 
## When 

* 매트릭스를 분해하는 가장 초보적인 방법 
* Eigenvalue 기반 분해, 혹은 Least squares에 두루두루 사용된다. 

## Where 

https://en.wikipedia.org/wiki/QR_decomposition

## What 

Any reeal square matrix $A$ may be decomposed as 

$$ A = QR $$, 

where $Q$ is an orthogonal matrix ($Q^T Q = Q Q^T = I$) and $R$ is an upper(right) triangular matrix. 

## How 

let 


* Basically we use Gram-Schmidt process.

$u_1 = a_1$,  $e_1 = \dfrac{u_1}{||u_1||}$

$u_2 = a_2 - \text{proj}_{u_1} a_2$,  $e_2 = \dfrac{u_2}{||u_2||}$

$u_3 = a_3 - \text{proj}_{u_1} a_3 - \text{proj}_{u_2} a_3$,  $e_2 = \dfrac{u_3}{||u_3||}$

$\vdots$

$u_k = a_k - \text{proj}_{u_1} a_3 - \text{proj}_{u_2} a_3$,  $e_2 = \dfrac{u_3}{||u_3||}$

## Why 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwNjIwNTc1OTIsLTg2MDk4NDgwMSwtMT
M0MjAxNzU5OV19
-->
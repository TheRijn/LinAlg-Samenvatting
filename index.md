---
title: Lineaire Algebra KI/INF Samenvatting
---
## Hoorcollege 1a

- [3blue1brown: Essence of linear algebra on Youtube](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

### 1.1 The Geometry and Algebra of Vectors

Theorem 1.1 <- Algebra $\mathbb{R}^n$
![](1.1/rules.png)

### 1.2 Length and Angle: The Dot Product

Dot product:
![](1.2/dot.png)
Norm (length):
![](1.2/norm.png)
Distance:
![](1.2/distance.png)
Angle between vectors:
![](1.2/angle.png)
Orthogonaal (hoek 90 graden):
![](1.2/orthogonal.png)
Pythagoras:
![](1.2/pythagoras.png)
(Orthogonal) Projection:
![](1.2/projectie.png)

## Hoorcollege 1b

### 1.3 Lines and Planes

![](1.3/table12.png)
$ \vec{n} \cdot \vec{x} = \delta $

Normaal-vector is de vector loodrecht op de lijn/vlak

![](1.3/table13.png)
$ \vec{n} \cdot \vec{x} = \delta $

#### Distance between plane and point



In 3d:<br>
$ \vec{n} \cdot \vec{x} = \delta $ geeft of een punt boven of onder een vlak ligt

|||
|---|---|
|$\> 0$ | boven het vlak|
|$= 0$ | op het vlak|
|$< 0$ | onder het vlak|

## Hoorcollege 2a

> RREF: Reduced Row-Echelon Form

span: de ruimte van vectoren die je kan maken van een set vectoren

### 2.1 Introduction to Systems of Linear Equations

![](2.1/lin_eq.png)

### 2.2 Direct Methods for Solving Linear Systems

![](2.2/REF.png)
![](2.2/ref_operation.png)
![](2.2/rref.png)
![](2.2/rank.png)
![](2.2/free_vars.png)

### 2.3 Spanning Sets and Linear Independence

Span:
De set van vectoren die je kan maken door een aantal andere vectoren te combineren
![](2.3/span.png)
![](2.3/lin_in_dependent.png)
Een vector is lineair afhankelijk als deze uitgedrukt kan worden met 

## Hoorcollege 2b

### 3.1 Matrix Operations

![](3.1/matrix_product.png)
![](3.1/matrix_transpose.png)
![](3.1/matrix_symmetric.png)

### 3.6 Introduction to Linear Transformations

![](3.6/linear_trans.png)
![](3.6/inverse_trans.png)

#### Types of (linear)transformations

Rotatie $\theta$ (tegen de klok in):

$T = \begin{bmatrix} 
\cos{\theta} & -\sin{\theta} \\\ 
\sin{\theta} & \cos{\theta} 
\end{bmatrix}$
$T^{-1} = \begin{bmatrix} 
\cos{\theta} & \sin{\theta} \\\ 
\-sin{\theta} & \cos{\theta} 
\end{bmatrix}$

## Hoorcollege 3a

### 3.2 Matrix Algebra

![](3.2/matrix_alg.png)
![](3.2/matrix_alg2.png)
![](3.2/transpose_prop.png)
![](3.2/symmetric_matrix.png)

$\frac{d \cdot d^T}{d^T \cdot d} \cdot v$


### 3.3 The Inverse of a Matrix

## Hoorcollge 3b


### 3.5: Subspace, Basis, Dimension and Rank

#### Linear Subspaces (Deelruimte)

![](3.5/subspace.png)

In 2D:

0-D a) $\vec{o}$ punt in de oorsprong <br/>
1-D b) Een lijn door $\vec{o}$ <br/>
2-D c) Hele vlak

![](3.5/subspace_def.png)

![](3.5/row_col_space.png)
$row(A) = col(A^T)$ $(row(A))^T = col(A^T)$ <br/>
col space, de ruimte van mogelijke uitkomsten

![](3.5/nullspace.png)
Alle vectoren die op $\vec{o}$ terechtkomen

##### Subspace of Transformation

Bij rotatie veranderd de subspace niet

#### Basis

![](3.5/basis.png)
Minimaal aantal vectoren die je nodig hebt om een subspace op te spannen en maximaal onafhankelijk

#### Dimension

![](3.5/dimension.png)
Het aantal vectoren in de Basis van een subspace

#### Null space or Kernel (NL: nulruimte of kern)

$null(A):$ deelruimte opgespannen door alle $\vec{x}$ waarvoor $A\vec{x}=0$

#### Rank

$rank(A):$ dimensie $col(A)$

#### Nullity
![](3.5/nullity.png)

De dimension van de nulruimte
$nullity(A):$ dimensie van $null(A)$

$A =m \times n$, dan geldt: <br>
$rank(A) + nullity(A) = n$

## Acknowledgements

Pictures © David Poole, Linear Algebra - A Modern Introduction (*Fourth edition*)

<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    extensions: ["tex2jax.js"],
    jax: ["input/TeX", "output/HTML-CSS"],
    tex2jax: {
      inlineMath: [ ['$','$'], ["\\(","\\)"] ],
      displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
      processEscapes: true
    },
    "HTML-CSS": { fonts: ["TeX"] }
  });
</script>
<script async src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js' type="text/javascript"></script>

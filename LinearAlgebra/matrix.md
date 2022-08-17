## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)


## Agenda
* Matrix Operations
* Special Matrices
* Matrix Decompositions

## Why we need Matrix Decomposition also known as Matrix Factorization?
So if you pre _multiply one vector by a matrix_ you get another _vector_.


### Trace of a Matrix
The trace of a matrix is given by the sum of its diagonal elements.
$$\large{\color{Purple}\mathit{Tr}\mathbf{(A) =\sum_{i} A_{ii}}}$$
#### Example
Suppose we have a matrix -

$$\large{\color{Purple}\mathbf{A} = \begin{bmatrix}
{\color{Cyan}1} & 4 & 5 \\
7 & {\color{Cyan}2} & 6 \\ 
8 & 9 & {\color{Cyan}3} \\
\end{bmatrix} 
} 
$$

The Trace of the matrix is - $\large {\color{Purple}Tr(\mathbf{A}) = 1+ 2+ 3= 6}$

The idea of trace you can use for **non-square** matrices also, so let us say this ${\color{Purple}\mathbf{A}_{3 \times 6}}$ is longer you had  you would still look at only <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{ii}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{ii}}" align="center"/> which are <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A_{11},A_{22},A_{33}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A_{11},A_{22},A_{33}}}" align="center"/> it would still be **6**, okay. So typically however we will be using trace for square matrices.

#### Proparties
$$
\begin{matrix}
 {\color{Purple} \mathbf{\ tr(A + B)}}& = & {\color{Purple} \mathbf{tr(A) + tr(B)}} \\
 {\color{Purple}\mathbf{\ tr(AB)}} & =& {\color{Purple} \mathbf{tr(BA)} [Even\ AB \neq BA]}\\ 
 {\color{Purple}\mathbf{\ tr(A)}} & =& {\color{Purple} \mathbf{tr(A^\top )}}
\end{matrix}
$$


### Determinant of a Matrix
In mathematics, the determinant is a **scalar** value that is a function of the entries of a **square matrix**. It allows characterizing some properties of the matrix and the linear map represented by the matrix. In particular, the determinant is nonzero if and only if the matrix is invertible and the linear map represented by the matrix is an isomorphism. The determinant of a product of matrices is the product of their determinants (the preceding property is a corollary of this one).
#### Easiest to define recursivly.

$$
\large {\color{Purple} \begin{bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
\end{bmatrix}= a_{11}a_{22}- a_{12}a_{21}}
$$

#### Laplace expansion: For a ${\color{Purple} n \times n}$ matrix **A**

$$ \large {\color{Purple} det(\textbf{A})= \sum_{j=1}^{n} (-1)^{i+j}\textbf{A}_{ij}\ det(\textbf{a}_{ij})}$$

* a<sub>ij</sub> is the sub matrix 

### Invertibility of a Matrix
#### A square matrix is invertible if and only if  ${\color{Purple} det(\mathbf{A}) \neq 0 } $

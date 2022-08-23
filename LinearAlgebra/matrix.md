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
In mathematics, the determinant is a **scalar** value that is a function of the entries of a **square matrix**. It allows characterizing some properties of the matrix and the linear map represented by the matrix. In particular, the determinant is nonzero if and only if the matrix is **invertible** and the linear map represented by the matrix is an **isomorphism**. The determinant of a product of matrices is the product of their determinants (the preceding property is a corollary of this one).

$$ \large
{\color{Purple}
{\displaystyle 
{\begin{aligned}|A|=
{\begin{bmatrix}
a&b\\
c&d
\end{bmatrix}}=ad-bc.\end{aligned}}}}
$$

#### Easiest to define recursivly.

$$
\large {\color{Purple} \begin{bmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22} \\
\end{bmatrix}= a_{11}a_{22}- a_{12}a_{21}}
$$

#### Laplace expansion: For a ${\color{Purple} n \times n}$ matrix **A**

$$ \large {\color{Purple} det(\textbf{A})= \sum_{j=1}^{n} (-1)^{i+j}\mathbf{A_{\textit{ij}}} \ det(\mathbf{a_{\textit{ij}}})}$$

* a<sub><i>ij</i></sub> is the sub matrix 

### Invertibility of a Matrix
#### A square matrix is invertible if and only if  ${\color{Purple} det(\mathbf{A}) \neq 0 } $


$$\large {\color{Purple} \mathbf{A^{-1}}} \textrm{exists if and only if } {\color{Purple} det(\mathbf{A})} \textrm{or} {\color{Purple} |A| \neq 0 } $$

#### Note that this automatically means that the columns of A have to be linearly independent


## Special Matrices and vectors

### 1 _Diagonal Matrix_ - Only diagonal entries are non-zero

$$\large {\color{Purple} \mathbf{D_{\textit{ij}} = 0},\ \ \textrm{if} \ \ i \neq j }  $$

### 2 _Symmetric Matrix_ - Matrix is equal to its transpose

$$\large {\color{Purple} \mathbf{A = A^{\top} }} $$

### 3 _Unit Vector_ - Vector with unit "length"( or Norm)

$$\large {\color{Purple} \mathbf{\parallel v \parallel= 1}} $$

* Usually we use **2 Norms** or $\large {\color{Purple} \mathbf{\parallel v \parallel_2}}$ or **Euclidean Norm**

### 4 _Orthogonal Vectors_ - Mutually perpendicular
$$\large {\color{Purple} \overrightarrow{\mathbf{x}}.\overrightarrow{\mathbf{y}}=0 \ \Rightarrow \ \mathbf{x^{\top}y=0}}  $$

* **Orthonormal Vctors :** Unit vectors perpendicular to each other.

### 5 _Orthogonal Matrix_ - Transpose is equal to inverse (e)
$$\large
{\color{Purple} 
\begin{matrix}
\mathbf{A^{\top}=A^{-1}}\\
\mathbf{\Rightarrow A^{\top}A = AA^{\top}=I}
\end{matrix}
} 
$$
* Simple Orthogonal Matrix is the identity matrix


### Eigen Decomposition
* This is typically very useful for **square symmetric matrices** specially square symmetric real matrices even though you can use it for other matrices as well and I am sure you would have done it before.

#### Physical meaning
Every real matrix can be thought of as a combination of rotation and stretching

* If you have a matrix  $\large {\color{Purple} \mathbf{A}}$ if it pre multiplies a vector $\large {\color{Purple} \overrightarrow{\mathbf{v}}}$, it results in some other vector $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$. Like-   <img src="https://latex.codecogs.com/svg.image?\large{\color{Purple}&space;\mathbf{A_{\mathit{n\times&space;n}}}&space;&space;\overrightarrow{\mathbf{v}}_{n&space;\times&space;i}&space;=&space;\overrightarrow{\mathbf{w}}_{n&space;\times&space;i}}" title="https://latex.codecogs.com/svg.image?\large{\color{Purple} \mathbf{A_{\mathit{n\times n}}} \overrightarrow{\mathbf{v}}_{n \times i} = \overrightarrow{\mathbf{w}}_{n \times i}}" />

<img src="https://user-images.githubusercontent.com/12748752/185712350-97fccc35-515d-44cc-9640-f7e914991b55.png" width=20% align="right"/>


Now you can think of $\large{\color{Purple} \mathbf{A}}$ as a machine or an operator acting on $\large{\color{Purple} \overrightarrow{\mathbf{v}}}$ and giving you $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$, takes $\large{\color{Purple} \overrightarrow{\mathbf{v}}}$ takes it to $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$,
Through physics as well as intuitively you can see that there are only two things that this matrix $\large {\color{Purple} \mathbf{A}}$ can do to $\large {\color{Purple} \overrightarrow{\mathbf{v}}}$, it can rotate it that is it can turn it through an angle even in **2D**, **3D** in any place that you can think of it turn it through an angle and the other thing it can do is: it can change its length,

### Eigenvectors

**Eigenvectors** are those special vectors for a given matrix 
$\large{\color{Purple} \mathbf{A}}$ , the eigenvectors 



$\large{\color{Purple} \overrightarrow{\mathbf{v}}}$  which  will only stretch under the action of this matrix.

### Eigenvalue
**Eigenvalue** is the factor by which this vector stretches

$$\large{\color{Purple} {\displaystyle \mathbf{A} \mathbf{v} =\lambda \mathbf {v} } }$$




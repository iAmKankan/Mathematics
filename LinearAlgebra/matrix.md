## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## Agenda
* Matrix Operations
* Special Matrices
* Matrix Decompositions
###  _Matrix Decomposition_ also known as _Matrix Factorization_
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
It is an approach that can simplify more complex matrix operations that can be performed on the decomposed matrix rather than on the original matrix itself. A simple decomposing is one big thing into smaller thing which we can understand a little bit better. It is also useful sometimes for a large matrix to be summarized by 1 or 2 or a fewer numbers rather than a large numbers.

### Why we need _Matrix Decomposition_ also known as _Matrix Factorization_?
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
1) Matrices transform one vector to another.
     * So if you pre _multiply one vector by a matrix_ you get another _vector_.
2) We will deal with high dimensional vectors and tensors
     * **Example:** _Images as an example of high dimensional vectors_. If you have a **60 &times; 60** _grayscale image_ you can interpret it as if it is a _single_ **3600** _dimensional vector_ or _one vector_ with **3600** components **pixel 1**, **pixel 2**, up till **pixel 3600**.
3) As with the prime factorization of numbers, it is useful to understand “components” of a matrix
     * So if we have to convert an **n &times; 1** vector suppose **V**  into another n **n &times; 1** vector suppose **W**,  you will have to **_pre multiply_** by a matrix suppose **A** which is **n &times; n**, okay which means if **n** = **3600**, then **A** is **3600 &times; 3600** matrix.

$$\Huge{\color{Purple}
\begin{align*}
A_{n \times n} \vec{V_{n \times 1}} \to \vec{W_{n \times 1}}
\end{align*}
}
$$

4) Also useful to get smaller set of representative numbers
   * **Example :** **Norms**, **Trace**, **Determinant**, **Eigenvalues**, **Singular Values**.

### Trace of a Matrix
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

The trace of a matrix is simply the sum of its diagonal elements of the matrix. 
$$\large{\color{Purple}\mathit{Tr}\mathbf{(A) =\sum_{i} A_{ii}}}$$

#### Example
Suppose we have a matrix -

$$\Huge{\color{Purple}\mathbf{A} = \begin{bmatrix}
{\color{Cyan}1} & 4 & 5 \\
7 & {\color{Cyan}2} & 6 \\ 
8 & 9 & {\color{Cyan}3} \\
\end{bmatrix} 
\begin{cases}
& Tr(\mathbf{A}) & = 1+ 2+ 3\\
& &= 6
\end{cases}
} 
$$

#### $\Large{\color{Blue}Notes:}$ 
* The **trace of a matrix** can use for **non-square** matrices also.
* So, let us say this $\large{\color{Purple}\mathrm{A_{3 \times 6}}}$ is longer you had  you would still look at only $\large{\color{Purple}\mathrm{A_{ii}}}$  which are $\large{\color{Purple}\mathrm{A_{11},A_{22},A_{33}}}$ it would still be **6**. 
* So typically however we will be using **trace** for **square matrices**.

#### Proparties

$$
\begin{align*}
 &{\color{Purple} \mathbf{\ tr(A + B)}}& = & {\color{Purple} \mathbf{tr(A) + tr(B)}} \\
 &{\color{Purple}\mathbf{\ tr(AB)}} & =& {\color{Purple} \mathbf{tr(BA)} [Even\ AB \neq BA]}\\ 
 &{\color{Purple}\mathbf{\ tr(A)}} & =& {\color{Purple} \mathbf{tr(A^\top )}}
\end{align*}
$$


### Determinant of a Matrix
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
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
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)


### 1 _Diagonal Matrix_ - 
Only diagonal entries are non-zero and rest of the entries are zero.

$$\Huge{\color{Purple}\mathbf{A} = \begin{bmatrix}
{\color{Blue}10} & 0 & 0 \\
0 & {\color{Blue}8} & 0 \\ 
0 & 0 & {\color{Blue}3} \\
\end{bmatrix} 
} 
$$


$$\large {\color{Purple} \mathbf{D_{\textit{ij}} = 0},\ \ \textrm{if} \ \ i \neq j }  $$

### 2 _Symmetric Matrix_ - Matrix is equal to its transpose

$$\large {\color{Purple} \mathbf{A = A^{\top} }} $$

### 3 _Unit Vector_ - Vector with unit "length"( or Norm)

$$\large {\color{Purple} \mathbf{\parallel v \parallel= 1}} $$

* Usually we use **2 Norms** or $\large {\color{Purple} \mathbf{\parallel v \parallel_2}}$ or **Euclidean Norm**

### 4 _Orthogonal Vectors_ - Mutually perpendicular
Another (usual) useful idea is that of orthogonal vectors, it simply means vectors that are mutually perpendicular which means **x**, if **x** and **y** are mutually orthogonal mean **x:y** is **0**, which remember can be written in this matrix form you take **x<sup>T</sup> y** and set that equal to **0**. We also have the idea of orthonormal vectors or orthonormal vector set, where you have unit vectors that are perpendicular to each other.

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

Now where do we use orthogonal matrix even though this is orthonormal column vectors we still call it orthogonal matrix, an orthogonal matrix typically can always be thought of as a rotational operation, okay what that means is if I have one vector I pre multiply it by something and all it does to that vector is simply rotates it without changing the length, the matrix which should have been used would always be orthogonal this can be proved we will not have time to show all that, but please do remember it whenever you see an orthogonal matrix please think a rotation matrix, okay that is another way to think about it.

### Eigen Decomposition or _Matrix Factorization_
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* This is typically very useful for **square symmetric matrices** specially square symmetric real matrices even though you can use it for other matrices as well and I am sure you would have done it before.

* **Extremely useful for square symmetric matrices** 
   * Used for other matrices as well

* **Physical meaning**
  * Every real **matrix** can be thought of as a combination of rotation and stretching 
      * There are only **two things** that this matrix **A** can do to **v**, 1) it can rotate it that is, it can turn it through an angle even in 2D, 3D in any place that you can think of it turn it through an angle and 2) the other thing it can do is: it can change its length. 
      * Summary **A** can do to **v** either **Rotate it** or **Streatch it**. 
  * For a matrix **Eigen vectors** are those **special vectors** that only **stretch** under the action of the matrix 
  * **Eigen values** are the **factor** by which **eigenvectors stretch**
  * So **Eigen Decomposition** is that **angle** in some sense or that set of **vectors** which only **stretch** under the action of the **matrix A**.

$$\Huge
{\color{Purple} 
\begin{align*}
& Av=\lambda v &
\end{align*}
\large\begin{cases}
\lambda v : \textit{ is a new vector 'W';}\\
\textit{But this 'W' is not rotated it is starached.}
\end{cases}
} 
$$


* If you have a matrix  $\large {\color{Purple} \mathbf{A}}$ if it pre multiplies a vector $\large {\color{Purple} \overrightarrow{\mathbf{v}}}$, it results in some other vector $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$. Like- 
<p align="center">
    <img src="https://github.com/iAmKankan/Mathematics/assets/12748752/e3638b40-d63f-4509-9038-3d18c0697a78" width=20% />
    <br>
    <img src="https://user-images.githubusercontent.com/12748752/185712350-97fccc35-515d-44cc-9640-f7e914991b55.png" width=20% />
</p>

Now you can think of $\large {\color{Purple} \mathbf{A}}$ as a machine or an operator acting on $\large{\color{Purple} \overrightarrow{\mathbf{v}}}$ and giving you $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$ , takes $\large{\color{Purple} \overrightarrow{\mathbf{v}}}$ takes it to $\large {\color{Purple} \overrightarrow{\mathbf{w}}}$, Through physics as well as intuitively you can see that there are only two things that this matrix $\large {\color{Purple} \mathbf{A}}$ can do to $\large {\color{Purple} \overrightarrow{\mathbf{v}}}$, it can rotate it that is it can turn it through an angle even in **2D**, **3D** in any place that you can think of it turn it through an angle and the other thing it can do is: it can change its length,

### Eigenvectors
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
**Eigenvectors** are those special vectors for a given matrix 
$\large{\color{Purple} \mathbf{A}}$ , the eigenvectors 



$\large{\color{Purple} \overrightarrow{\mathbf{v}}}$  which  will only stretch under the action of this matrix.

### Eigenvalue
**Eigenvalue** is the factor by which this vector stretches

$$\large{\color{Purple} {\displaystyle \mathbf{A} \mathbf{v} =\lambda \mathbf {v} } }$$




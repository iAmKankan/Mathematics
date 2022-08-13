## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [Linear Algebra](#linear-algebra)
   * [Scalar](#scalar)
   * [Vector](#vector)
   * [Difference between Scalar and Vector quantities](#difference-between-scalar-and-vector-quantities)
   * [Length, Dimensionality and Shape](#length-dimensionality-and-shape)
   * [Matrix](#matrix)
      * [Properties of Matrix]()
   * [Tensors](#tensors)
* [Geometry of Vectors](#geometry-of-vectors)
   * [Dot Products and Angles](#dot-products-and-angles)
   * [Cosine Similarity](#cosine-similarity)
   
## Linear Algebra
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
Linear Algebra, mathematical discipline that deals with **vectors** and **matrices** and, more generally, with **vector spaces** and **linear transformations**. 

### Scaler
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
_A Scaalr is a number_. It is a physical quantity that is completely described by its magnitude(size); examples of scalars are **volume**, **density**, **speed**, **energy**, **mass**, and **time**. 

Other quantities, such as **force** and **velocity**, have both magnitude(size) and direction and are called **_vectors_**.

Scalars are described by _real numbers_ that are _usually but not necessarily positive_. Scalars can be manipulated by the ordinary laws of algebra.

#### Example:
* Let <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha&space;\in&space;\mathbb{R}}&space;}" title="{\color{Purple}\mathbf{\alpha \in \mathbb{R}} }" align ="center"/>, be the _learning rate_.
* Let <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\eta&space;\in&space;\mathbb{N}}&space;}" title="{\color{Purple}\mathbf{\eta \in \mathbb{N}} }" align ="center"/>, be the _number of hyperparameters_.
* Scalar quantities change when their magnitude changes.

### Vector
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A **vector** in machine learning is simply an **array of numbers**. 

In **physics**, Vector is a quantity that has both **magnitude** and **direction**. 

In **Computer Science Vector** is a data in _tabuler form_ having _rows_ and _columns_. 
   *  A vector is just an array of numbers.
   *  Every vector has a length. 
   *  In mathematics notation- If we want to say that a vector  _x_  consists of  _n_  real-valued scalars, we can express this as <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;x\in&space;\mathbb{R}^n}" title="https://latex.codecogs.com/svg.image?{\color{Purple} x\in \mathbb{R}^n}" />.
   *  The _length_ of a vector is commonly called the _dimension_ of the vector.
   *  When a tensor represents a vector (with precisely one axis), we can also access its length via the .shape attribute. The shape is a tuple that lists the length (dimensionality) along each axis of the tensor. For tensors with just one axis, the shape has just one element.

#### Example #1
* Let say <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{x}&space;\in&space;\mathbb{R}^n}&space;}" title="{\color{Purple}\mathbf{\overrightarrow{x} \in \mathbb{R}^n} }" />, be the inpuit vector. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix}&space;{\color{Purple}x_1}\\&space;{\color{Purple}x_2}\\{\color{Purple}\vdots&space;}\\{\color{Purple}x_n}\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix} {\color{Purple}x_1}\\ {\color{Purple}x_2}\\{\color{Purple}\vdots }\\{\color{Purple}x_n}\end{bmatrix}}" align="center"/>
 
* <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{11m\&space;east\&space;and\&space;15ms^{-1}\&space;at\&space;30^{\circ}&space;}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{11m\ east\ and\ 15ms^{-1}\ at\ 30^{\circ} }}" /> to the horizontal are both vector quantities.

#### Vector qualities include - 
* displacement
* velocity
* acceleration
* force
* weight
* momentum

#### Vector quantities change when:
* their magnitude changes
* their direction changes
* their magnitude and direction both change

#### Example #2
* A geostationary satellite is in orbit above Earth. It moves at constant speed but its velocity is constantly changing (since its direction is always changing).

### Difference between Scalar and Vector quantities
* **Speed** is a scalar quantity – **it is the rate of change in the distance travelled by an object.**
* While **velocity** is a **vector quantity** – **it is the speed of an object in a particular direction.**

### Matrix
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
In **Machine Learning**, matrix is a **2-D array** of numbers. In Computer Science, a **matrix** is a **_multidimensional array_**. 

#### Example #1
* Let <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{W}=\mathbb{R}^{m\times&space;n}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{W}=\mathbb{R}^{m\times n}}" />, be the matrix of weight.

### Difference between Vector and Matrix -
*  A **matrix** is a rectangular array of numbers while a **vector** is a list of number. 
*  Vector have one index, matrix having two index.

### Tensors
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
In Machine Learning, Tensors are array of numbers with **dimensions greater than two(2)**.

_The general term of **Scalars**, **Vectors** and **Matrix** is **Tensors**._ The use of **Tensors** or **multi-dimensional matrices** Google named the package "Tensorflow".

#### Example #1
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

Just as **vectors** generalize **scalars**, and **matrices** generalize **vectors**. **Tensors** ("tensors" in this subsection refer to algebraic objects) give us a generic way of describing  **n -dimensional arrays** with an arbitrary number of axes.

**Vectors** are **first-order tensors** and **Matrix** are **second-order tensors**. Tensors are denoted with capital letters of a special font face (e.g.,  **X** ,  **Y** , and  **Z** ) and their **indexing mechanism** (e.g. <img src="https://latex.codecogs.com/svg.image?\large&space;{\color{Purple}\&space;\&space;x_{ijk}\&space;\&space;and\&space;\&space;[X]_{1,2i-1,3}}" title="https://latex.codecogs.com/svg.image?\large {\color{Purple}\ \ x_{ijk}\ \ and\ \ [X]_{1,2i-1,3}}" />) is similar to that of **matrices**.


### Tensors types
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

#### Scalar(**0<sup>th</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3} }" align="center"/>

#### Vector (**1<sup>st</sup>** order **Tensor**)  <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}}&space;=&space;\begin{bmatrix}&space;1\\&space;2\\&space;3\\4\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}} = \begin{bmatrix} 1\\ 2\\ 3\\4\end{bmatrix}}" align="center"/>, The dimension of this Vector is 4, (<img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\textbf{Dimension&space;of&space;a&space;Vector&space;=&space;the&space;number&space;of&space;elements}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \textbf{Dimension of a Vector = the number of elements} }" align="center"/>)

#### Matrix (**2<sup>nd</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{i,j}}=&space;\begin{bmatrix}1&space;&&space;2&space;&space;&&space;3&space;\\4&space;&&space;5&space;&&space;5&space;\\\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{i,j}}= \begin{bmatrix}1 & 2 & 3 \\4 & 5 & 5 \\\end{bmatrix}}" align="center"/>

#### Tensor (**3<sup>rd</sup>** and higher order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

#### Example
* Colour images, Video data( **4<sup>th</sup>** order tensors coz series of images)

## Basic Operations
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
### Topics-

* **Addition**, **Broadcasting**(a special type of addition)
* **Multiplication**
   * **Matrix product**, **Dot product** and **Hadamard Product**(_elimentwise multiplication_)
* **Matrix Transpose** 
* **Matrix Inverse**

### <ins>_Addition_ and _Broadcasting_ of Matrix</ins> 
#### ◼️ _Normal Addition_ <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{i,j}&plus;&space;B_{i,j}&space;=&space;C_{i,j}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{i,j}+ B_{i,j} = C_{i,j}}}" align="center" />

* If <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A[a_{ji}]_{m\times&space;n}}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A[a_{ji}]_{m\times n}}} " align="center" /> and <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{B[b_{ji}]_{m\times&space;n}}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{B[b_{ji}]_{m\times n}}} " align="center" /> are two matrices of the same order then their sum **A + B** is a matrix <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{{\color{Purple}&space;\mathbf{[C_{ji}]_{m\times&space;n}}}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{{\color{Purple} \mathbf{[C_{ji}]_{m\times n}}}}}" align="center" />, and each element of that matrix is the sum of the corresponding elements. i.e. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A&plus;B=[a_{ji}&plus;b_{ji}]_{m\times&space;n}}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A+B=[a_{ji}+b_{ji}]_{m\times n}}} "  /> 

#### Example
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\begin{bmatrix}a_1&space;&&space;b_1&space;\\c_1&space;&&space;d_1&space;\\\end{bmatrix}&space;&plus;\begin{bmatrix}a_2&space;&&space;b_2&space;\\c_2&space;&&space;d_2&space;\\\end{bmatrix}&space;=\begin{bmatrix}a_1&plus;a_2&space;&&space;b_1&plus;b_2&space;\\c_1&plus;c_2&space;&&space;d_1&plus;d_2&space;\\\end{bmatrix}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} \begin{bmatrix}a_1 & b_1 \\c_1 & d_1 \\\end{bmatrix} +\begin{bmatrix}a_2 & b_2 \\c_2 & d_2 \\\end{bmatrix} =\begin{bmatrix}a_1+a_2 & b_1+b_2 \\c_1+c_2 & d_1+d_2 \\\end{bmatrix}} " align="center" />

#### ◼️ _Broadcasting_ <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{ij}&plus;&space;b_{j}&space;=&space;C_{ij}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{ij}+ b_{j} = C_{ij}}}" align="center"/>
* It can be done, only if the vector that we are choosing either has the same number of rows or the same number of columns matches with the matrix.
* We repeat the vector as if its a matrix of the same size.
* Adding a vector to a matrix by repeating the vector.
* Done autometically by MATLAB and Numpy.
* In Numpy, also this kind of addition is done automatically it is assumed that, if you have a size mismatch then, you actually have broadcasting going on.
#### Example
Suppose we have a matrix <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{i,j}}=&space;\begin{bmatrix}1&space;&&space;2&space;&space;&&space;3&space;\\4&space;&&space;5&space;&&space;5&space;\\\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{i,j}}= \begin{bmatrix}1 & 2 & 3 \\4 & 5 & 5 \\\end{bmatrix}}" align="center"/> and a vector(or a row matrix) is <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{b}_j=&space;\begin{bmatrix}&space;1&&space;1&space;&&space;1&space;\\\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{b}_j= \begin{bmatrix} 1& 1 & 1 \\\end{bmatrix}}" align="center" />

* This <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[&space;1,&space;1,&space;1&space;]}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[ 1, 1, 1 ]}}" align="center"/>, gets added to the **1<sup>st</sup>(first) row** gives you- <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[&space;2,&space;3,&space;4&space;]}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[ 2, 3, 4 ]}}" align="center"/>, it also gets added to the **2<sup>nd</sup>(second) row** which is- <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[&space;4,&space;5,&space;5&space;]}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[ 4, 5, 5 ]}}" align="center" /> and gives you- <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[&space;5,&space;6,&space;6&space;]}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{[ 5, 6, 6 ]}}" align="center"/>.

#### Properties of Matrix Addition: If A, B and C are matrices of same order, then-
1. Commutative Law: **A + B = B + A**
2. Associative Law:  **(A + B) + C = A + (B + C)**
3. Identity of the Matrix: **A + O =  O + A = A**, where **O** is zero matrix which is additive identity of the matrix,
4. Additive Inverse: **A + (-A) = 0 = (-A) + A**, where **(-A)** is obtained by changing the sign of every element of **A** which is additive inverse of the matrix,
5. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\left.\begin{matrix}A&plus;B&space;&&space;=&space;&&space;A&plus;C&space;\\B&plus;A&space;&&space;=&space;&&space;C&plus;A&space;\\\end{matrix}\right\}\Rightarrow&space;B=C&space;}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} \left.\begin{matrix}A+B & = & A+C \\B+A & = & C+A \\\end{matrix}\right\}\Rightarrow B=C } " align="center"/>
6. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;tr(A\pm&space;B)=tr(A)\pm&space;tr(B)&space;}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple} tr(A\pm B)=tr(A)\pm tr(B) } " align="center" />
7. If **A + B = 0 = B + A**, then **B** is called additive inverse of **A** and also **A** is called the additive inverse of **A**.

### <ins>_Multiplication_ of Matrix</ins> 
#### ◼️ _Matrix Product_ <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{C&space;=&space;AB}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{C = AB}}" align="center"/>
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{C_{ij}&space;=}\sum_{k}\&space;\mathbf{A}_{ik}\mathbf{B}_{kj}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{C_{ij} =}\sum_{k}\ \mathbf{A}_{ik}\mathbf{B}_{kj}}" align="center"/>

* The size of the two matrix **A** and **B** must match, 
* Multiplication of two matrices involves dot products between **all the rows of first matrix** and **all the columns of the second matrix**. 

* <img src="https://latex.codecogs.com/svg.image?\textrm{If&space;}&space;{\color{Purple}\mathbf{A}}&space;\textrm{&space;is&space;a&space;}{\color{Purple}m&space;\times&space;n}&space;\textrm{&space;matrix&space;and&space;}{\color{Purple}\mathbf{B}}&space;\textrm{&space;is&space;a&space;}&space;{\color{Purple}n&space;\times&space;p}&space;\textrm{&space;matrix&space;then&space;their&space;product&space;}({\color{Purple}\mathbf{A.B}})&space;\textrm{&space;would&space;be&space;a&space;}&space;{\color{Purple}m&space;\times&space;p}&space;\textrm{&space;matrix,&space;}&space;{\color{Purple}\mathbf{C}_{m&space;\times&space;p}}" title="https://latex.codecogs.com/svg.image?\textrm{If } {\color{Purple}\mathbf{A}} \textrm{ is a }{\color{Purple}m \times n} \textrm{ matrix and }{\color{Purple}\mathbf{B}} \textrm{ is a } {\color{Purple}n \times p} \textrm{ matrix then their product }({\color{Purple}\mathbf{A.B}}) \textrm{ would be a } {\color{Purple}m \times p} \textrm{ matrix, } {\color{Purple}\mathbf{C}_{m \times p}}" align="center"/>

* A matrix can be Multiplied with a **column matrix** or **vector**.

<img src="https://user-images.githubusercontent.com/12748752/132519557-d232aedb-4676-4043-8f07-d87c8e9f87bb.png" />

#### Example
* <img src="https://latex.codecogs.com/svg.image?\textrm{If&space;}&space;{\color{Purple}\mathbf{A}}&space;\textrm{&space;is&space;a&space;}{\color{Purple}m&space;\times&space;n}&space;\textrm{&space;matrix&space;and&space;}{\color{Purple}\mathbf{B}}&space;\textrm{&space;is&space;a&space;}&space;{\color{Purple}n&space;\times&space;p}&space;\textrm{&space;matrix&space;then&space;their&space;product&space;}({\color{Purple}\mathbf{A.B}})&space;\textrm{&space;would&space;be&space;a&space;}&space;{\color{Purple}m&space;\times&space;p}&space;\textrm{&space;matrix,&space;}&space;{\color{Purple}\mathbf{C}_{m&space;\times&space;p}}" title="https://latex.codecogs.com/svg.image?\textrm{If } {\color{Purple}\mathbf{A}} \textrm{ is a }{\color{Purple}m \times n} \textrm{ matrix and }{\color{Purple}\mathbf{B}} \textrm{ is a } {\color{Purple}n \times p} \textrm{ matrix then their product }({\color{Purple}\mathbf{A.B}}) \textrm{ would be a } {\color{Purple}m \times p} \textrm{ matrix, } {\color{Purple}\mathbf{C}_{m \times p}}" align="center"/>

<img src="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle&space;\mathbf&space;{A}&space;={\begin{bmatrix}a_{11}&a_{12}&\cdots&space;&a_{1n}\\a_{21}&a_{22}&\cdots&space;&a_{2n}\\\vdots&space;&\vdots&space;&\ddots&space;&\vdots&space;\\a_{m1}&a_{m2}&\cdots&space;&a_{mn}\\\end{bmatrix}},\quad&space;\mathbf&space;{B}&space;={\begin{bmatrix}b_{11}&b_{12}&\cdots&space;&b_{1p}\\b_{21}&b_{22}&\cdots&space;&b_{2p}\\\vdots&space;&\vdots&space;&\ddots&space;&\vdots&space;\\b_{n1}&b_{n2}&\cdots&space;&b_{np}\\\end{bmatrix}}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle \mathbf {A} ={\begin{bmatrix}a_{11}&a_{12}&\cdots &a_{1n}\\a_{21}&a_{22}&\cdots &a_{2n}\\\vdots &\vdots &\ddots &\vdots \\a_{m1}&a_{m2}&\cdots &a_{mn}\\\end{bmatrix}},\quad \mathbf {B} ={\begin{bmatrix}b_{11}&b_{12}&\cdots &b_{1p}\\b_{21}&b_{22}&\cdots &b_{2p}\\\vdots &\vdots &\ddots &\vdots \\b_{n1}&b_{n2}&\cdots &b_{np}\\\end{bmatrix}}}}" />

##### Therefore, A &sdot;B can also be written as

<img src="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle&space;\mathbf&space;{C}&space;={\begin{bmatrix}a_{11}b_{11}&plus;\cdots&space;&plus;a_{1n}b_{n1}&a_{11}b_{12}&plus;\cdots&space;&plus;a_{1n}b_{n2}&\cdots&space;&a_{11}b_{1p}&plus;\cdots&space;&plus;a_{1n}b_{np}\\a_{21}b_{11}&plus;\cdots&space;&plus;a_{2n}b_{n1}&a_{21}b_{12}&plus;\cdots&space;&plus;a_{2n}b_{n2}&\cdots&space;&a_{21}b_{1p}&plus;\cdots&space;&plus;a_{2n}b_{np}\\\ddots&space;&\ddots&space;&\ddots&space;&\ddots&space;\\a_{m1}b_{11}&plus;\cdots&space;&plus;a_{mn}b_{n1}&a_{m1}b_{12}&plus;\cdots&space;&plus;a_{mn}b_{n2}&\cdots&space;&a_{m1}b_{1p}&plus;\cdots&space;&plus;a_{mn}b_{np}\\\end{bmatrix}}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle \mathbf {C} ={\begin{bmatrix}a_{11}b_{11}+\cdots +a_{1n}b_{n1}&a_{11}b_{12}+\cdots +a_{1n}b_{n2}&\cdots &a_{11}b_{1p}+\cdots +a_{1n}b_{np}\\a_{21}b_{11}+\cdots +a_{2n}b_{n1}&a_{21}b_{12}+\cdots +a_{2n}b_{n2}&\cdots &a_{21}b_{1p}+\cdots +a_{2n}b_{np}\\\ddots &\ddots &\ddots &\ddots \\a_{m1}b_{11}+\cdots +a_{mn}b_{n1}&a_{m1}b_{12}+\cdots +a_{mn}b_{n2}&\cdots &a_{m1}b_{1p}+\cdots +a_{mn}b_{np}\\\end{bmatrix}}}}" />


#### ◼️ _Hadamard Product_ (_Elimentwise Multiplication_) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{C=A&space;\odot&space;B}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{C=A \odot B}}"  align="center"/>
* This technique is similar to matrix addition.
* Hadamard Product has several advantages, linear algebra wise it turns out that more often they use in deep learning and in machine learning, we see this kind of elementwise multiplication.

#### Usage 
* Hadamard product is used in image compression techniques such as JPEG. It is also known as Schur product( the result of Hadamard Product or **A &odot B** = **C**, here **C** is the Schur product)
* Hadamard Product is used in **LSTM** (Long Short-Term Memory) cells of Recurrent Neural Networks (**RNNs**).

#### Example
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle&space;{\begin{bmatrix}a_{11}&a_{12}&a_{13}\\a_{21}&a_{22}&a_{23}\\a_{31}&a_{32}&a_{33}\end{bmatrix}}\odot&space;{\begin{bmatrix}b_{11}&b_{12}&b_{13}\\b_{21}&b_{22}&b_{23}\\b_{31}&b_{32}&b_{33}\end{bmatrix}}={\begin{bmatrix}a_{11}\,b_{11}&a_{12}\,b_{12}&a_{13}\,b_{13}\\a_{21}\,b_{21}&a_{22}\,b_{22}&a_{23}\,b_{23}\\a_{31}\,b_{31}&a_{32}\,b_{32}&a_{33}\,b_{33}\end{bmatrix}}.}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple}{\displaystyle {\begin{bmatrix}a_{11}&a_{12}&a_{13}\\a_{21}&a_{22}&a_{23}\\a_{31}&a_{32}&a_{33}\end{bmatrix}}\odot {\begin{bmatrix}b_{11}&b_{12}&b_{13}\\b_{21}&b_{22}&b_{23}\\b_{31}&b_{32}&b_{33}\end{bmatrix}}={\begin{bmatrix}a_{11}\,b_{11}&a_{12}\,b_{12}&a_{13}\,b_{13}\\a_{21}\,b_{21}&a_{22}\,b_{22}&a_{23}\,b_{23}\\a_{31}\,b_{31}&a_{32}\,b_{32}&a_{33}\,b_{33}\end{bmatrix}}.} }" />
<img src="https://user-images.githubusercontent.com/12748752/184334723-45a452b9-ea57-4ce9-b8d2-222b86125a29.png" width="30%"/>

#### ◼️ _Dot Product_  <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{a}&space;\cdot&space;\overrightarrow{b}=\alpha}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{a} \cdot \overrightarrow{b}=\alpha}}" /> (_Vector_ notation) or <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha}=&space;\mathbf{a^\top&space;b}&space;=\mathbf{b^\top&space;a}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha}= \mathbf{a^\top b} =\mathbf{b^\top a}}" /> (_Matrix_ notation)

<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha&space;=}&space;\mathbf{\sum}_{i}&space;\mathbf{a}_i&space;\mathbf{b}_i}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha =} \mathbf{\sum}_{i} \mathbf{a}_i \mathbf{b}_i}" />

* For **Machine Learning** we use this **Dot Product**, **cross product** or **Matrix Product** is generally used in Physics.
* _As we know the the dot product of two **vector** gives a **Scaler**_. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{a}&space;\cdot&space;\overrightarrow{b}=\alpha}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{a} \cdot \overrightarrow{b}=\alpha}}" align="center"/>

<img src="https://latex.codecogs.com/svg.image?\\\textrm{If&space;}&space;{\color{Purple}\mathbf{a=}\textbf{[1&space;2&space;3]&space;&space;}&space;}&space;\textrm{&space;and&space;}&space;{\color{Purple}\mathbf{b=}\textbf{[4&space;5&space;6]&space;}&space;}\textrm{&space;then&space;the&space;dot&space;of&space;the&space;two&space;is-&space;}&space;{\color{Purple}\mathbf{a.b^\top&space;=&space;\alpha}&space;}&space;\textrm{&space;or&space;}&space;{\color{Purple}&space;\textbf{[1&space;2&space;3]}&space;\cdot&space;\begin{bmatrix}4&space;\\5&space;\\6\end{bmatrix}}&space;\\{\color{Purple}\mathbf{\alpha}&space;}&space;=&space;{\color{Purple}\mathbf{[(4&space;\times&space;1)&plus;&space;(5&space;\times&space;2)&space;&plus;&space;(6&space;\times&space;3)]&space;=\&space;32}}&space;\textrm{,&space;which&space;is&space;a&space;Scaler.}" title="https://latex.codecogs.com/svg.image?\\\textrm{If } {\color{Purple}\mathbf{a=}\textbf{[1 2 3] } } \textrm{ and } {\color{Purple}\mathbf{b=}\textbf{[4 5 6] } }\textrm{ then the dot of the two is- } {\color{Purple}\mathbf{a.b^\top = \alpha} } \textrm{ or } {\color{Purple} \textbf{[1 2 3]} \cdot \begin{bmatrix}4 \\5 \\6\end{bmatrix}} \\{\color{Purple}\mathbf{\alpha} } = {\color{Purple}\mathbf{[(4 \times 1)+ (5 \times 2) + (6 \times 3)] =\ 32}} \textrm{, which is a Scaler.}" />


#### Properties of Scalar Multiplication: If A, B are matrices of the same order and λ and μ are any two scalars then
1. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\lambda&space;(&space;A&plus;B&space;)=\lambda&space;A&plus;\lambda&space;B\lambda&space;(A&plus;B)=\lambda&space;A&plus;\lambda&space;B}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\lambda ( A+B )=\lambda A+\lambda B\lambda (A+B)=\lambda A+\lambda B}" />
2. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}(&space;\lambda&space;&plus;\mu&space;)A=\lambda&space;A&plus;\mu&space;A(\lambda&space;&plus;\mu&space;)A=\lambda&space;A&plus;\mu&space;A}" title="https://latex.codecogs.com/svg.image?{\color{Purple}( \lambda +\mu )A=\lambda A+\mu A(\lambda +\mu )A=\lambda A+\mu A}" />
3. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\lambda&space;(&space;\mu&space;A&space;)=(&space;\lambda&space;\,\mu&space;A&space;)=\mu&space;(&space;\lambda&space;A&space;)\lambda&space;(\mu&space;A)=(\lambda&space;\mu&space;A)=\mu&space;(\lambda&space;A)}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\lambda ( \mu A )=( \lambda \,\mu A )=\mu ( \lambda A )\lambda (\mu A)=(\lambda \mu A)=\mu (\lambda A)}" />
4. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}{(&space;-&space;\lambda&space;A&space;)=&space;-&space;(\lambda&space;A&space;)&space;=&space;\lambda(-A)}" title="https://latex.codecogs.com/svg.image?{\color{Purple}{( - \lambda A )= - (\lambda A ) = \lambda(-A)}" />
5. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}{tr&space;(&space;kA&space;)=k&space;tr(A)}" title="https://latex.codecogs.com/svg.image?{\color{Purple}{tr ( kA )=k tr(A)}" /> 


### <ins>_Matrix Transpose_</ins> <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{B&space;=&space;A^\top&space;}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{B = A^\top }}" />

<img src="https://user-images.githubusercontent.com/12748752/184396146-ea23685c-7ca2-4fd5-a366-536f4848e4c3.gif" width=60%/>

![](https://en.wikipedia.org/wiki/Transpose#/media/File:Matrix_transpose.gif)

#### Example
1) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{{\displaystyle&space;{\begin{bmatrix}1&2\end{bmatrix}}^{\top&space;}=\,{\begin{bmatrix}1&space;\\2\end{bmatrix}}}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{{\displaystyle {\begin{bmatrix}1&2\end{bmatrix}}^{\top }=\,{\begin{bmatrix}1 \\2\end{bmatrix}}}}}" align="center" />
2) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;{\displaystyle&space;{\begin{bmatrix}1&2\\3&4\end{bmatrix}}^{\top&space;}={\begin{bmatrix}1&3\\2&4\end{bmatrix}}}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} {\displaystyle {\begin{bmatrix}1&2\\3&4\end{bmatrix}}^{\top }={\begin{bmatrix}1&3\\2&4\end{bmatrix}}}}" align="center"/>
3) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;{\displaystyle&space;{\begin{bmatrix}1&2\\3&4\\5&6\end{bmatrix}}^{\top&space;}={\begin{bmatrix}1&3&5\\2&4&6\end{bmatrix}}}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple} {\displaystyle {\begin{bmatrix}1&2\\3&4\\5&6\end{bmatrix}}^{\top }={\begin{bmatrix}1&3&5\\2&4&6\end{bmatrix}}} }" align="center"/>


![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

### Cosine Similarity
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In ML contexts where the angle is employed to measure the closeness of two vectors, practitioners adopt the term cosine similarity to refer to the portion
> <img src="https://latex.codecogs.com/svg.image?cos(\theta)\&space;=\&space;\mathrm{\frac{v.w}{\parallel&space;v\parallel\parallel&space;w\parallel}&space;&space;}" title="cos(\theta)\ =\ \mathrm{\frac{v.w}{\parallel v\parallel\parallel w\parallel} }" />

> * The cosine takes a maximum value of  1  when the two vectors point in the same direction, 
> * A minimum value of  −1  when they point in opposite directions,
> * A value of  0  when the two vectors are orthogonal.( _We say that 2 vectors are orthogonal if they are perpendicular to each other. i.e. the dot product of the two vectors is zero_).
*  Note that if the components of high-dimensional vectors are sampled randomly with mean  0 , their cosine will nearly always be close to  0 .

## References:
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [NPTEL](https://www.youtube.com/watch?v=NDq_VaZ3iSQ&list=PLyqSpQzTE6M-SISTunGRBRiZk7opYBf_K&index=4)


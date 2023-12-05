## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
### [_Linear Algebra_](#what-is-linear-algebra)
* [Scalar](#scaler)
* [Vector](#vector)
    * [Difference between Scalar and Vector quantities](#difference-between-scalar-and-vector-quantities)
* [Matrix](#matrix)
   * [Difference between Vector and Matrix](#difference-between-vector-and-matrix)
* [Tensors](#tensors)
   * [Tensors Orders](#tensors-orders)
### [Vector Space](https://github.com/iAmKankan/Mathematics/blob/main/LinearAlgebra/vector_space.md)
### [Matrix in depth](https://github.com/iAmKankan/Mathematics/blob/main/LinearAlgebra/matrix.md)
### [_Basic Operations on Linear algebra_](https://github.com/iAmKankan/Mathematics/blob/main/LinearAlgebra/basic-operations.md)

### [_Norms_](https://github.com/iAmKankan/Mathematics/blob/main/LinearAlgebra/norms.md)
[**Cosine Similarity**](#cosine-similarity)

### [_References_](#references)

![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
## What is Linear Algebra?
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
Linear Algebra is a mathematical discipline that deals with **vectors** and **matrices** and more generally, with **vector spaces** and **linear transformations**. 

### Scaler
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
_A Scaalr is a number_. It is a physical quantity that is completely described by its _magnitude(size)_; examples of scalars are **volume**, **density**, **speed**, **energy**, **mass**, and **time**. 

Other quantities, such as **force** and **velocity**, have both _magnitude(size)_ and _direction_ and are called **_vectors_**.

**Scalars** are described by _real numbers_ that are _usually but not necessarily positive_. **Scalars** can be manipulated by the ordinary laws of algebra.

#### Example:
* Let $\large{\color{Purple}\mathbf{\alpha \in \mathbb{R}}}$ , be the _learning rate_.
* Let $\large{\color{Purple}\mathbf{\eta \in \mathbb{N}}}$ , be the _number of hyperparameters_.

_Scalar quantities_ change when their _magnitude_ changes.

### Vector
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A **vector** in machine learning is simply an **array of numbers**. 

In **physics**, Vector is a quantity that has both **magnitude** and **direction**. 

In **Computer Science Vector** is a data in _tabuler form_ having _rows_ and _columns_. 
   *  A vector is just an array of numbers.
   *  Every vector has a length. 
   *  In mathematics notation- If we want to say that a vector  <img src="https://latex.codecogs.com/svg.image?\large{\color{Purple}&space;x}" title="https://latex.codecogs.com/svg.image?\large{\color{Purple} x}" /> consists of <img src="https://latex.codecogs.com/svg.image?\large{\color{Purple}&space;n}" title="https://latex.codecogs.com/svg.image?\large{\color{Purple} n}" /> real-valued scalars, we can express this as <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;x\in&space;\mathbb{R}^n}" title="https://latex.codecogs.com/svg.image?{\color{Purple} x\in \mathbb{R}^n}" />.
   *  The <ins><i>length</i></ins> of a vector is commonly called the <ins><i>dimension</i></ins> of the vector.
   *  When a tensor represents a vector (with precisely one axis), we can also access its length via the .shape attribute. The shape is a tuple that lists the length (dimensionality) along each axis of the tensor. For tensors with just one axis, the shape has just one element.

#### Example #1
* Let say <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{x}&space;\in&space;\mathbb{R}^n}&space;}" title="{\color{Purple}\mathbf{\overrightarrow{x} \in \mathbb{R}^n} }" />, be the input vector. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix}&space;{\color{Purple}x_1}\\&space;{\color{Purple}x_2}\\{\color{Purple}\vdots&space;}\\{\color{Purple}x_n}\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}x=\begin{bmatrix} {\color{Purple}x_1}\\ {\color{Purple}x_2}\\{\color{Purple}\vdots }\\{\color{Purple}x_n}\end{bmatrix}}" align="center"/>
 
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

### Difference between Vector and Matrix
*  A **matrix** is a rectangular array of numbers while a **vector** is a list of number. 
*  Vector have one index, matrix having two index.

### Tensors
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
In Machine Learning, Tensors are array of numbers with **dimensions greater than two(2)**.

_The general term of **Scalars**, **Vectors** and **Matrix** is **Tensors**._ The use of **Tensors** or **multi-dimensional matrices** Google named the package "Tensorflow".

#### Example #1
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

> ### Just as **vectors** generalize **scalars**, and **matrices** generalize **vectors**. **Tensors** ("tensors" in this subsection refer to algebraic objects) give us a generic way of describing  **n -dimensional arrays** with an arbitrary number of axes.

**Vectors** are **first-order tensors** and **Matrix** are **second-order tensors**. Tensors are denoted with capital letters of a special font face (e.g.,  **X** ,  **Y** , and  **Z** ) and their **indexing mechanism** (e.g. <img src="https://latex.codecogs.com/svg.image?\large&space;{\color{Purple}\&space;\&space;x_{ijk}\&space;\&space;and\&space;\&space;[X]_{1,2i-1,3}}" title="https://latex.codecogs.com/svg.image?\large {\color{Purple}\ \ x_{ijk}\ \ and\ \ [X]_{1,2i-1,3}}" />) is similar to that of **matrices**.


### Tensors Orders
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

#### Scalar(**0<sup>th</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha=3} }" align="center"/>

#### Vector (**1<sup>st</sup>** order **Tensor**)  <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}}&space;=&space;\begin{bmatrix}&space;1\\&space;2\\&space;3\\4\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}} = \begin{bmatrix} 1\\ 2\\ 3\\4\end{bmatrix}}" align="center"/>, The dimension of this Vector is 4, (<img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\textbf{Dimension&space;of&space;a&space;Vector&space;=&space;the&space;number&space;of&space;elements}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \textbf{Dimension of a Vector = the number of elements} }" align="center"/>)

#### Matrix (**2<sup>nd</sup>** order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\mathbf{A_{i,j}}=&space;\begin{bmatrix}1&space;&&space;2&space;&space;&&space;3&space;\\4&space;&&space;5&space;&&space;5&space;\\\end{bmatrix}}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \mathbf{A_{i,j}}= \begin{bmatrix}1 & 2 & 3 \\4 & 5 & 5 \\\end{bmatrix}}" align="center"/>

#### Tensor (**3<sup>rd</sup>** and higher order **Tensor**) <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{A}_{i,j,k}}" />

#### Example
* Colour images, Video data( **4<sup>th</sup>** order tensors coz series of images)


### Cosine Similarity
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In ML contexts where the angle is employed to measure the closeness of two vectors, practitioners adopt the term cosine similarity to refer to the portion
> <img src="https://latex.codecogs.com/svg.image?cos(\theta)\&space;=\&space;\mathrm{\frac{v.w}{\parallel&space;v\parallel\parallel&space;w\parallel}&space;&space;}" title="cos(\theta)\ =\ \mathrm{\frac{v.w}{\parallel v\parallel\parallel w\parallel} }" />

> * The cosine takes a maximum value of  1  when the two vectors point in the same direction, 
> * A minimum value of  −1  when they point in opposite directions,
> * A value of  0  when the two vectors are orthogonal.( _We say that 2 vectors are orthogonal if they are perpendicular to each other. i.e. the dot product of the two vectors is zero_).
*  Note that if the components of high-dimensional vectors are sampled randomly with mean  0 , their cosine will nearly always be close to  0 .

## References
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [NPTEL(NOC:Machine Learning for Engineering and Science Applications, IIT Madras Prof. Balaji Srinivasan, Prof. Ganapathy)](https://nptel.ac.in/courses/106106198)


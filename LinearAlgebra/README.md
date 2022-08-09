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


### Linear Algebra
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
Linear Algebra, mathematical discipline that deals with **vectors** and **matrices** and, more generally, with **vector spaces** and **linear transformations**. 

### Scaler
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A Scaalr is a number. It is a physical quantity that is completely described by its magnitude(size); examples of scalars are **volume**, **density**, **speed**, **energy**, **mass**, and **time**. 

Other quantities, such as **force** and **velocity**, have both magnitude(size) and direction and are called **_vectors_**.

Scalars are described by _real numbers_ that are _usually but not necessarily positive_. Scalars can be manipulated by the ordinary laws of algebra.

#### Example:
* Let <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\alpha&space;\in&space;\mathbb{R}}&space;}" title="{\color{Purple}\mathbf{\alpha \in \mathbb{R}} }" align ="center"/>, be the _learning rate_.
* Let <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\eta&space;\in&space;\mathbb{N}}&space;}" title="{\color{Purple}\mathbf{\eta \in \mathbb{N}} }" align ="center"/>, be the _number of hyperparameters_.
* Scalar quantities change when their magnitude changes.

### Vector
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A **vector** in machine learning is simply an **array of numbers**. 

#### Example:
* Let say <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\overrightarrow{x}&space;\in&space;\mathbb{R}^n}&space;}" title="{\color{Purple}\mathbf{\overrightarrow{x} \in \mathbb{R}^n} }" />, be the inpuit vector. 

Now, typically in physics or even in hard core mathematics, vectors have very specific meanings, we are not looking at that we are looking at any, even if it is an unconnected series of numbers, for example, x1 could be height, x2 could be weight, xn could be number of people. So, you can put together, any num- ber of things together, all of those put together as long as you concatenate it into a column, we call it a vector, x. So, please do remember this is a bold letter, bold small letters, we will typically use this for vectors or sometimes we might even use something like !x .

* In physics, a quantity that has both magnitude and direction. 
* In Computer Science Vector is a data in tabuler form having rows and columns.
* Vector vs matrix -
   *  A matrix is a rectangular array of numbers while a vector is a list of number. 
   *  Vector have one index, matrix having two index.

* **Vector quantities** have both magnitude and direction. 
> #### For example
> * <img src="https://latex.codecogs.com/svg.image?\mathrm{11m\&space;east\&space;and\&space;15ms^{-1}\&space;at\&space;30^{\circ}&space;}&space;" title="\mathrm{11m\ east\ and\ 15ms^{-1}\ at\ 30^{\circ} } " /> to the horizontal are both vector quantities.
> * Vector qualities include
>   * displacement
>   * velocity
>   * acceleration
>   * force
>   * weight
>   * momentum

* Vector quantities change when:
> * their magnitude changes
> * their direction changes
> * their magnitude and direction both change

### Difference between Scalar and Vector quantities
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Speed is a scalar quantity – **it is the rate of change in the distance travelled by an object.**
* While velocity is a vector quantity – **it is the speed of an object in a particular direction.**

> #### Example
> * A geostationary satellite is in orbit above Earth. 
> * It moves at constant speed but its velocity is constantly changing (since its direction is always changing).

* The difference in two vectors quantities = final vector - initial vector
* The difference in two scalar quantities = large value - small value

### Length Dimensionality and Shape
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* A vector is just an array of numbers.
*  Every vector has a length. 
> #### In mathematics notation- If we want to say that a vector  x  consists of  n  real-valued scalars, we can express this as 
>>  <img src="https://latex.codecogs.com/svg.image?x\in&space;\mathbb{R}^n" title="x\in \mathbb{R}^n" />. 
* The length of a vector is commonly called the dimension of the vector.
* When a tensor represents a vector (with precisely one axis), we can also access its length via the .shape attribute. The shape is a tuple that lists the length (dimensionality) along each axis of the tensor. For tensors with just one axis, the shape has just one element.
### Matrix
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* If <img src="https://latex.codecogs.com/svg.image?A[a_{ji}]_{mXn}" title="A[a_{ji}]_{mXn}" /> and <img src="https://latex.codecogs.com/svg.image?B[b_{ji}]_{mXn}" title="B[b_{ji}]_{mXn}" /> are two matrices of the same order then their sum A + B is a matrix, and each element of that matrix is the sum of the corresponding elements. i.e. <img src="https://latex.codecogs.com/svg.image?A&plus;B&space;=&space;[a_{ji}&plus;b_{ji}]_{mXn}" title="A+B = [a_{ji}+b_{ji}]_{mXn}" />
* Sum of the two matrix
* <img src="https://latex.codecogs.com/svg.image?\begin{vmatrix}a1&space;&&space;b1&space;\\c1&space;&&space;d1&space;\\\end{vmatrix}&space;&plus;\begin{vmatrix}a2&space;&&space;b2&space;\\c2&space;&&space;d2&space;\\\end{vmatrix}&space;=\begin{vmatrix}a1&plus;a2&space;&&space;b1&plus;b2&space;\\c1&plus;c2&space;&&space;d1&plus;d2&space;\\\end{vmatrix}&space;" title="\begin{vmatrix}a1 & b1 \\c1 & d1 \\\end{vmatrix} +\begin{vmatrix}a2 & b2 \\c2 & d2 \\\end{vmatrix} =\begin{vmatrix}a1+a2 & b1+b2 \\c1+c2 & d1+d2 \\\end{vmatrix} " />
#### Properties of Matrix Addition: If A, B and C are matrices of same order, then-
(a) Commutative Law: A + B = B + A

(b) Associative Law:  (A + B) + C = A + (B + C)

(c) Identity of the Matrix: A + O =  O + A = A, where O is zero matrix which is additive identity of the matrix,

(d) Additive Inverse: A + (-A) = 0 = (-A) + A, where (-A) is obtained by changing the sign of every element of A which is additive inverse of the matrix,

(e) <img src="https://latex.codecogs.com/svg.image?\left.\begin{matrix}A&plus;B&space;&&space;=&space;&&space;A&plus;C&space;\\B&plus;A&space;&&space;=&space;&&space;C&plus;A&space;\\\end{matrix}\right\}\Rightarrow&space;B=C" title="\left.\begin{matrix}A+B & = & A+C \\B+A & = & C+A \\\end{matrix}\right\}\Rightarrow B=C" />

(f) <img src="https://latex.codecogs.com/svg.image?tr(A\pm&space;B)=tr(A)\pm&space;tr(B)" title="tr(A\pm B)=tr(A)\pm tr(B)" />

(g) If A + B = 0 = B + A, then B is called additive inverse of A and also A is called the additive inverse of A.


#### Properties of Scalar Multiplication: If A, B are matrices of the same order and λ and μ are any two scalars then
1. <img src="https://latex.codecogs.com/svg.image?\lambda&space;&space;(&space;A&plus;B&space;)=\lambda&space;&space;A&plus;\lambda&space;&space;B\lambda&space;(A&plus;B)=\lambda&space;A&plus;\lambda&space;B" title="\lambda ( A+B )=\lambda A+\lambda B\lambda (A+B)=\lambda A+\lambda B" />
1. <img src="https://latex.codecogs.com/svg.image?(&space;\lambda&space;&space;&plus;\mu&space;&space;)A=\lambda&space;&space;A&plus;\mu&space;&space;A(\lambda&space;&plus;\mu&space;)A=\lambda&space;A&plus;\mu&space;A" title="( \lambda +\mu )A=\lambda A+\mu A(\lambda +\mu )A=\lambda A+\mu A" />
1. <img src="https://latex.codecogs.com/svg.image?\lambda&space;&space;(&space;\mu&space;&space;A&space;)=(&space;\lambda&space;&space;\,\mu&space;&space;A&space;)=\mu&space;&space;(&space;\lambda&space;&space;A&space;)\lambda&space;(\mu&space;A)=(\lambda&space;\mu&space;A)=\mu&space;(\lambda&space;A)" title="\lambda ( \mu A )=( \lambda \,\mu A )=\mu ( \lambda A )\lambda (\mu A)=(\lambda \mu A)=\mu (\lambda A)" />
1. <img src="https://latex.codecogs.com/svg.image?(&space;-&space;\lambda&space;&space;A&space;)=&space;-&space;(\lambda&space;A&space;)&space;=&space;\lambda(-A)" title="( - \lambda A )= - (\lambda A ) = \lambda(-A)" />
1.  tr ( kA )=k tr(A) 

#### Properties of matrix multiplication
* For matrix multiplication, the number of columns in the first matrix must be equal to the number of rows in the second matrix.
*  The resulting matrix, known as the matrix product, has the number of rows of the first and the number of columns of the second matrix. 
*  The product of matrices A and B is denoted as AB.
![matrixMul](https://user-images.githubusercontent.com/12748752/132519557-d232aedb-4676-4043-8f07-d87c8e9f87bb.png)


* If A is an m × n matrix and B is an n × p matrix,

* <img src="https://latex.codecogs.com/svg.image?{\displaystyle&space;\mathbf&space;{A}&space;={\begin{pmatrix}a_{11}&a_{12}&\cdots&space;&a_{1n}\\a_{21}&a_{22}&\cdots&space;&a_{2n}\\\vdots&space;&\vdots&space;&\ddots&space;&\vdots&space;\\a_{m1}&a_{m2}&\cdots&space;&a_{mn}\\\end{pmatrix}},\quad&space;\mathbf&space;{B}&space;={\begin{pmatrix}b_{11}&b_{12}&\cdots&space;&b_{1p}\\b_{21}&b_{22}&\cdots&space;&b_{2p}\\\vdots&space;&\vdots&space;&\ddots&space;&\vdots&space;\\b_{n1}&b_{n2}&\cdots&space;&b_{np}\\\end{pmatrix}}}" title="{\displaystyle \mathbf {A} ={\begin{pmatrix}a_{11}&a_{12}&\cdots &a_{1n}\\a_{21}&a_{22}&\cdots &a_{2n}\\\vdots &\vdots &\ddots &\vdots \\a_{m1}&a_{m2}&\cdots &a_{mn}\\\end{pmatrix}},\quad \mathbf {B} ={\begin{pmatrix}b_{11}&b_{12}&\cdots &b_{1p}\\b_{21}&b_{22}&\cdots &b_{2p}\\\vdots &\vdots &\ddots &\vdots \\b_{n1}&b_{n2}&\cdots &b_{np}\\\end{pmatrix}}}" />



* Therefore, AB can also be written as


<img src="https://latex.codecogs.com/svg.image?{\displaystyle&space;\mathbf&space;{C}&space;={\begin{pmatrix}a_{11}b_{11}&plus;\cdots&space;&plus;a_{1n}b_{n1}&a_{11}b_{12}&plus;\cdots&space;&plus;a_{1n}b_{n2}&\cdots&space;&a_{11}b_{1p}&plus;\cdots&space;&plus;a_{1n}b_{np}\\a_{21}b_{11}&plus;\cdots&space;&plus;a_{2n}b_{n1}&a_{21}b_{12}&plus;\cdots&space;&plus;a_{2n}b_{n2}&\cdots&space;&a_{21}b_{1p}&plus;\cdots&space;&plus;a_{2n}b_{np}\\\vdots&space;&\vdots&space;&\ddots&space;&\vdots&space;\\a_{m1}b_{11}&plus;\cdots&space;&plus;a_{mn}b_{n1}&a_{m1}b_{12}&plus;\cdots&space;&plus;a_{mn}b_{n2}&\cdots&space;&a_{m1}b_{1p}&plus;\cdots&space;&plus;a_{mn}b_{np}\\\end{pmatrix}}}" title="{\displaystyle \mathbf {C} ={\begin{pmatrix}a_{11}b_{11}+\cdots +a_{1n}b_{n1}&a_{11}b_{12}+\cdots +a_{1n}b_{n2}&\cdots &a_{11}b_{1p}+\cdots +a_{1n}b_{np}\\a_{21}b_{11}+\cdots +a_{2n}b_{n1}&a_{21}b_{12}+\cdots +a_{2n}b_{n2}&\cdots &a_{21}b_{1p}+\cdots +a_{2n}b_{np}\\\vdots &\vdots &\ddots &\vdots \\a_{m1}b_{11}+\cdots +a_{mn}b_{n1}&a_{m1}b_{12}+\cdots +a_{mn}b_{n2}&\cdots &a_{m1}b_{1p}+\cdots +a_{mn}b_{np}\\\end{pmatrix}}}" />



### Tensors
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Just as vectors generalize scalars, and matrices generalize vectors, we can build data structures with even more axes. 
* Tensors ("tensors" in this subsection refer to algebraic objects) give us a generic way of describing  n -dimensional arrays with an arbitrary number of axes.
*  Vectors, for example, are first-order tensors, and matrices are second-order tensors. Tensors are denoted with capital letters of a special font face (e.g.,  X ,  Y , and  Z ) and their indexing mechanism (<img src="https://latex.codecogs.com/svg.image?e.g.\&space;\&space;x_{ijk}\&space;\&space;and\&space;\&space;&space;[X]_{1,2i-1,3}" title="e.g.\ \ x_{ijk}\ \ and\ \ [X]_{1,2i-1,3}" />) is similar to that of matrices.





![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)




### Geometry of Vectors
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* There are two common geometric interpretations of vectors, as either **points** or **directions** in space.
*  Fundamentally, a vector is a list of numbers such as the Python list below.
```python
v = [1, 7, 0, 1]
```
* Mathematicians most often write this as either a **column vector** or **row vector**, which is to say either as

### Dot Products and Angles
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* If we take two column vectors  u  and  v , we can form their dot product by computing:
> <img src="https://latex.codecogs.com/svg.image?u^{T}v\&space;=\&space;\sum_{i}u_i.v_i" title="u^{T}v\ =\ \sum_{i}u_i.v_i" />

### Cosine Similarity
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In ML contexts where the angle is employed to measure the closeness of two vectors, practitioners adopt the term cosine similarity to refer to the portion
> <img src="https://latex.codecogs.com/svg.image?cos(\theta)\&space;=\&space;\mathrm{\frac{v.w}{\parallel&space;v\parallel\parallel&space;w\parallel}&space;&space;}" title="cos(\theta)\ =\ \mathrm{\frac{v.w}{\parallel v\parallel\parallel w\parallel} }" />

> * The cosine takes a maximum value of  1  when the two vectors point in the same direction, 
> * A minimum value of  −1  when they point in opposite directions,
> * A value of  0  when the two vectors are orthogonal.( _We say that 2 vectors are orthogonal if they are perpendicular to each other. i.e. the dot product of the two vectors is zero_).
*  Note that if the components of high-dimensional vectors are sampled randomly with mean  0 , their cosine will nearly always be close to  0 .


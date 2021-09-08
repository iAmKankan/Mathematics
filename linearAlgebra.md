### Linear Algebra:
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
#### Why Linear Algebra?
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

* Part of math which is used the most in Machine Learning
* Helps in optimization
* Perform operations on the data
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

### 1. Scalar:
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Scalar, a physical quantity that is completely described by its magnitude; examples of scalars are volume, density, speed, energy, mass, and time.
* Magnetude but no direction is Scalar.
* Other quantities, such as force and velocity, have both magnitude and direction and are called **vectors.**

* Scalars are described by real numbers that are usually but not necessarily positive.
* The work done on a particle by a force, for example, is a negative number when the particle moves in a direction opposite to that in which the force acts.
* Scalars can be manipulated by the ordinary laws of algebra.

### 2. Vector:
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In physics, a quantity that has both magnitude and direction. 
* In Computer Science Vector is a data in tabuler form having rows and columns.
* Vector vs matrix - A matrix is a rectangular array of numbers while a vector is a list of number. Vector have one index matrix having two index.
### 3. Matrix:
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

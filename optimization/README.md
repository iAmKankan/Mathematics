## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

### _Prerequisite_
#### [◼️ _Derivatives Theory_](#derivatives)
   * [_Partial Derivative_](#partial-derivative)
#### [◼️ _Gradien Theory_](#gradient), [◼️ _Hessian_](#hessian) , [◼️ _Jacobian_](#jacobian), [◼️ _Taylor Series_](#taylor-series)

### ◼️ Optimization 

### [_References and Bibliography_](#references)

## Derivatives
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
In mathematics, the **derivative of a function of a real variable** measures the sensitivity to change of the **function value** (**output value 'y'** ) with respect to a change in its **argument** (**input value 'x'**)

**Derivative** typically measures _**how one quantity changes when there is a small change in another**_. _It is essential for any type of **optimisation**_.

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/185729977-fb75f65b-c829-4e3c-9011-778e66fa4614.png" width=25% />
    <img src="https://user-images.githubusercontent.com/12748752/191807903-de529575-ea90-4427-bfb7-1c00bb187e2e.png" width=30%/>
  <img src="https://user-images.githubusercontent.com/12748752/185731247-dd55fb41-9147-4d1c-88a6-b3501efc15d4.png" width=25% />
</p>


#### Example
If you have something like $\large{\color{Purple}\displaystyle{\frac{dY}{dX}}}$ it means how much does ${\color{Purple}Y}$ change given that ${\color{Purple}X}$ changes buy a certain amount

In the left side, if this is the **curve** $\large {\color{Purple} y = f(x)}$ and a point let us say $\large {\color{Purple} p}$, if we differentiate $\large {\color{Purple} y}$ with respect to $\large {\color{Purple} x}$ at $\large {\color{Purple} x\ = \ p}$ we will get the **slope** of the **tangent**. 

#### We can denote this as-
* **_`dy`_ by _`dx`_ at _`x`_ equal to `p` $\large{\color{Purple}\displaystyle{\frac{dy}{dx}[x = p]}}$ or $\LARGE{\color{Purple}\left.{\frac {dy}{dx}}\right|_{x=p}}$ or**
* **_`f`_ prime _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (p)}}$ or  _`f`_ prime _`x`_ equals _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (x = p)}}$**


**Geometrically**, in **one dimension**, this can be given as the **slope** of the **tangent** and it is expressed by a **scalar** function. like-

$$\large{\color{Purple} 
\boxed{f^\prime(a)}=\boxed{\frac{df}{dx}(x=a)} =\boxed{ \lim_{h\to 0}\frac{f(x+h)-f(x)}{h}}
}
$$

`f(x + h) – f(x)`  by `h`, this of course is the limits of this [secant](https://en.wikipedia.org/wiki/Secant_line#:~:text=In%20geometry%2C%20a%20secant%20is,circle%20at%20exactly%20two%20points.), as they go towards this point and become a **tangent**, so the slope at this point `x` and `x + h`, so we find out the difference in values and as this limit tends to `0`, **the slope** will tend to a **finite value** and that is what we call **_the derivative of the slope at that point_**.

## Partial Derivative
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
In **higher dimensions**, it simply mean you still have a **scalar function** but now **X**  is a vector ${\color{Purple}\mathbf{\vec{X}}}$. 
* So in that case, ${\color{Purple}\mathbf{\vec{X}}}$ could be something like let us say ${\color{Purple}\mathbf{\vec{X}= (X_1, X_2, X_3); \vec{X}\in} \mathbb{R}^3}$, or. 
* It could be ${\color{Purple}\mathbf{\vec{X}= (X_1, X_2); \vec{X}\in} \mathbb{R}^2}$,
* So in such a case we can have partial derivative, so let us look at such an example let us say ${\color{Purple}\mathbf{Z = F( X , Y)}}$

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/191878109-992d3387-4dd8-48ed-9b62-ea9618f94ea7.png" width=40%/>
  <br><ins><b>A graph of <i>z = x<sup>2</sup> + xy + y<sup>2</sup></i>. For the partial derivative at (1, 1) that leaves <i>y</i> constant, the corresponding tangent line is parallel to the xz-plane.</b></i></ins>
</p>

#### Example:
Let us say ${\color{Purple} Z = f(x,y)}$, now if you want to denote or visualize **Z**, you simply have the variables **X** and **Y**, as they change **Z** changes and you see here 1 whole surface okay for Z.
 
##### Now, What is $\Huge{\color{Purple}\frac{\partial z}{\partial x} }$ at a particular point ? 
Let us say a point (at the middle of the curve) I want to know-
* If I change **X** and I keep **Y** fix, how much does **Z** changes.
$$\Huge{\color{Purple} \left. \frac{\partial z}{\partial x}\right|_{\textit{y fixed}} }$$

More generalized form-

$$
\large{\color{Purple}\begin{aligned}
\frac {\partial }{\partial x_{i}}f(a_1,\ldots,a_n)& = \lim_{h\to 0} {\frac{f(a_1,\ldots ,a_{i-1},a_{i}+h,a_{i+1},\ldots ,a_{n})-f(a_{1},\ldots ,a_{i},\dots ,a_{n})}{h}}\\ 
& = \lim _{h\to 0}{\frac {f(\mathbf {a} +h\mathbf{e_i} )-f(\mathbf {a} )}{h}}
\end{aligned}}
$$

Above **_f_** is a function that takes in a vector $\vec{a}$, which is in real number **&#x211D;** with total has **n** number of components and it gives back a single **scalar** **&#x211D;** .It looks like $\large{\color{Purple} f: \mathbb{R}^n \to \mathbb{R}}$ 


<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/191927759-8baa83a8-1a42-45ed-b93a-ba200dcacefe.png" width=20%/>
</p>

* Now reduced to a **one-dimensional** problem this is what it would look like, this is simply the cross-section of this function at **Y equal to 1** $\large{\color{Purple} \left. \frac{\partial z}{\partial x}\right|_{y =1} }$ and 
* If I want the slope. ${\color{Purple} \Huge\frac{\partial z}{\partial x} \normalsize \textrm{[x=1, y=1]} }$
* then I take a cross-section, where **Y** is fixed at **1** and evaluate the slope at **X** equal to **1** by just changing **X** and that slope will actually gave me the value of this partial derivative.

## Gradient
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
#### _How to Compute Gradient?_
The **gradient** captures all the **partial derivative** information of a **scalar-valued** **multivariable function**. (**scalar-valued multivariable functions**, meaning those with a **multidimensional input** but a **one-dimensional output**)

The **gradient of a function** $\large f$, denoted as $\large \nabla f$, is the collection of **all its partial derivatives** into **a vector**.

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192076320-c7406177-fbc6-4a3e-b8d3-23503a35bb35.png" width =50%/>
 </p>

#### Example #1:
Suppose we have a two variable function $\large f(x,y)$, now we need to findout the partial derivatives of the function. 
* Partial derivative for **x**, while **y** keep as constant which is $\large 2x \sin(y)$
* Partial derivative for **y**, now **x** keep as constant which is $\large x^2 \cos(y)$ 

$$\Huge{\color{Purple}
\begin{aligned}
{\color{Blue}f(x,y) }&{\color{Blue}= x^2 \sin(y)}\\ 
\frac{\partial f}{\partial x} &= 2x \sin(y)\\
\frac{\partial f}{\partial y} &= x^2 \cos(y)\\
\end{aligned}
\begin{aligned}
\\ 
\Big \\} \boxed{\nabla f(x,y)= \begin{bmatrix}2x \sin(y)\\
x^2 \cos(y)
\end{bmatrix}}
\end{aligned}
\begin{aligned}
\\
& & & \normalsize \textit{In general        }
\Huge\boxed{\nabla f(x,y,\ldots)= \begin{bmatrix}\frac{\partial f}{\partial x}\\
\frac{\partial f}{\partial y}\\
\vdots
\end{bmatrix}}
\end{aligned}
}
$$

* The gradient of a scalar-valued multivariable function $\large{\color{Purple}f(x, y, \dots)}$, denoted $\large{\color{Purple}\nabla f}$, packages all its partial derivative information into a vector:

$$\Huge{\color{Purple}
\nabla f(x_1,x_2,\ldots,x_n)= \begin{bmatrix} \frac{\partial f}{{\color{Blue}\partial x_1}}\\
\frac{\partial f}{{\color{Blue}\partial x_2}}\\
\vdots\\
\frac{\partial f}{{\color{Blue}\partial x_n}}\\
\end{bmatrix}
}
$$

In particular, this means $\large{\color{Purple}\nabla f}$ is a vector-valued function.
* If you imagine standing at a point $\large{\color{Purple}(x_0, y_0, \dots)}$  in the input space of $\large{\color{Purple}f}$, the vector $\large{\color{Purple}\nabla f(x_0, y_0, \dots)}$  tells you which direction you should travel to increase the value of $\large{\color{Purple}f}$ most rapidly.
* These gradient vectors— $\large{\color{Purple}\nabla f(x_0, y_0, \dots)}$ — are also perpendicular to the contour lines of $\large{\color{Purple}f}$.

#### Example #2
<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192133935-e42b650e-3ae0-4a73-b604-e6d57525afce.png" width=50%/>
</p>

Suppose we ahave a curve $\Large{\color{Purple}z=f(x,y)}$ , how much does the **value of the function change** at this **point** if the value of **x** changes.
* You have partial derivative of **x** as well as that of **y** - $\Large{\color{Purple}\frac{\partial f}{\partial x}}$ and $\Large{\color{Purple}\frac{\partial f}{\partial y}}$
* Instead of just looking at these two directions like -
    * $\Large{\color{Purple}\frac{\partial f}{\partial x}}$, would be the change in the direction of **x** and 
    * $\Large{\color{Purple}\frac{\partial f}{\partial y}}$, would be the change in direction of **y**.
* You could ask for the 3rd direction, I could call it as $\Large{\color{Purple}\frac{\partial f}{\partial v}}$, where **v** is some arbitrary direction okay. 
* So if this is **x**, this is **y** and **v** could be some 3rd direction altogether.

So the gradient is defined as basically a concatenation or putting together of all these partial derivative, so in this case with the two-dimensional case we have to search partial derivatives, in the n dimensional case you will have n such partial derivatives and you would basically write the gradient of F in my case would be 

$$\Huge{\color{Purple}
\nabla f(x,y)= \begin{bmatrix} \frac{\partial f}{\partial x}\\
\frac{\partial f}{\partial y}\\
\end{bmatrix}
}
$$

### Contours
Now imagine this curve here, imagine it is a bunch of springs and you just collapse it and you will see in the center, this projection here are called contours.
<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192134275-e32902ad-47f9-4cb1-9bff-3684a9cf0b22.png" width=50%/>
</p>

#### What does the contour mean? 
**Answer:** If I take this contour and raise it up to the curve(doted line in cylindric shape), it has all the values at this cylindric places of **x** and **y** all of these places **z** has the same value, so these are what are called **level sets** or **contours**

Now this right hand side picture is shaded according to value for example, in the center the value of the function is high, in the edges the value of the function is low so the places where the **value of the function is high** is **shaded as dark black** and later on it is shaded white okay. 

Now the gradient notice is a vector and the direction of the gradient tells you in which direction is the change the sharpest okay, so the change is the highest in the direction of the gradient okay. So in this case for example all the change is the sharpest in the horizontal direction okay. This of course is colour-coded now okay red means high, blue means low so this is just simply colour-coded but it is the same idea. Some of you who have worked in fluid mechanics might have seen this or even in other fields. So now you notice this, these are arrows here and the arrows are aligned along the direction of maximum change.

### The Gradient Field
Now if you have a more complex curve something like this, you can draw **the gradient field**,
<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192138269-5a1b8495-b4b9-4968-987c-97fa4ab289df.png" width=45%/>
</p>

#### It can be used to calculate the directional partial derivative of $\large 𝑓$ along the direction $\large \hat{𝒗}$ 

$$\Huge{\color{Purple}
D_v f (x) \lim_{\alpha \to 0} \frac{\partial f(x+\alpha \hat{v})}{\partial \alpha} = \nabla_x f({x}). \hat{v}
}
$$

I have an function and I have $\large{\color{Purple}\frac{\partial f}{\partial x_1}}$ and I have $\large{\color{Purple}\frac{\partial f}{\partial x_2}}$, these 2 put together define a **vector** and that **vector** is what is drawn here, longer arrows means higher gradients and shorter arrows means lower gradient.
Now one useful way of utilising the gradient vector is as I told you before, you might not only want $\large{\color{Purple}\frac{\partial f}{\partial x}}$ and $\large{\color{Purple}\frac{\partial f}{\partial y}}$, you might also want $\large{\color{Purple}\frac{\partial f}{\partial v}}$, where **v** is some other direction. So suppose **x** and **y** are orthogonal and **v** is a 3rd direction, 
* Suppose you want $\large{\color{Purple}\frac{\partial f}{\partial v}}$, what does that mean? 
* Physically it means if I move it in the direction **v** or &hat; v, how much will the function change? And this is fairly easy, all you do is take the gradient which we have defined before, this is $\large{\color{Purple}\frac{\partial f}{\partial x_1}}$ and $\large{\color{Purple}\frac{\partial f}{\partial x_2}}$ so on and so forth up to $\large{\color{Purple}\frac{\partial f}{\partial x_n}}$, this vector dotted with the direction **v** ok. 
* You can simply see special cases if **v** was $\hat{i}$ okay or the X_1 direction then gradient in the direction V should be Del F Del X 1 which is correct okay, so this retains the meaning of partial derivatives. Similarly, if you take the direction 2 you will get Del F Del X 2 so on and so forth, so for the coordinate axis this kind of reduces trivially but in the general case you simply take a dot product along that direction.

## Hessian
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* The **Hessian** is the **gradient** of the **gradient**.
  * It is the equivalent of the **second derivative** in scalar calculus and has similar uses
* For $\Large{\color{Purple}f:\mathbb{R}^n\to \mathbb{R}}$ , we have $\Large{\color{Purple}H_{i,j}=\frac{\partial^2 f}{\partial x_i \partial x_j}}$ is the Hessian which is a $\Large{\color{Purple}n \times m}$ matrix.

$$\Huge{\color{Purple}
H_{i,j} =
\begin{bmatrix}
\frac{\partial^2 f}{\partial x_1 \partial x_1} & \frac{\partial^2 f}{\partial x_1 \partial x_2}& \cdots&\frac{\partial^2 f}{\partial x_1 \partial x_n}\\
\frac{\partial^2 f}{\partial x_2 \partial x_1} & \frac{\partial^2 f}{\partial x_2 \partial x_2}& \cdots&\frac{\partial^2 f}{\partial x_2 \partial x_n}\\
\vdots & \vdots & \ddots & \vdots \\
\frac{\partial^2 f}{\partial x_n \partial x_1} & \frac{\partial^2 f}{\partial x_n \partial x_2}& \cdots&\frac{\partial^2 f}{\partial x_n \partial x_n}\\
\end{bmatrix}
\in \mathbb{R}^{n \times n}
}
$$

* Note that the **Hessian** is a **symmetric matrix**( $A^{\top} = A$ )
* So hessian is a symmetric matrix and from our linear algebra we would know that from real F this means hessian has [_real eigenvalues_](https://github.com/iAmKankan/Mathematics/blob/main/LinearAlgebra/matrix.md#eigen-decomposition-or-matrix-factorization)

## Jacobian
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
The Jacobian is the equivalent of the **gradient** for **vector valued** functions.
* Simple gradient is from scalar to vector $\large{\color{Purple} (\nabla) Scalar \to Vector}$ where its assume that the value of the function is scalar. 
* Whereas  Hessian takes a gradient as of **_f_** as scalar and gives a vector $\large{\color{Purple} Hessian \[\nabla f \] \to \nabla^2 f }$


For  $\large{\color{Purple}f: \mathbb{R}^n \to  \mathbb{R}^m}$ , we have $\large{\color{Purple} J_{i,j}=\frac{{\partial}^2 f(x)_{i}}{\partial x_j}}$ is the Jacobian which is a $\large{\color{Purple}j \in  \mathbb{R}^{m \times m}}$

$$\Huge{\color{Purple}
j= \nabla_x f =
\begin{bmatrix}
\frac{\partial^2 f_1}{\partial x_1 } & \frac{\partial^2 f_1}{ \partial x_2}& \cdots&\frac{\partial^2 f_1}{\partial x_n}\\
\frac{\partial^2 f_2}{\partial x_1} & \frac{\partial^2 f_2}{\partial x_2}& \cdots&\frac{\partial^2 f_2}{\partial x_n}\\
\vdots & \vdots & \ddots & \vdots \\
\frac{\partial^2 f_m}{\partial x_1} & \frac{\partial^2 f_m}{\partial x_2}& \cdots&\frac{\partial^2 f_m}{ \partial x_n}\\
\end{bmatrix}
\in \mathbb{R}^{m \times n}
}
$$


## Taylor Series
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
Taylor’s series is extremely useful whenever you try to approximate functions. 

The Taylor series is a local approximation of a function’s value in terms of polynomials 
* It is an extremely useful and widely used idea in multiple fields
* There are mathematical subtleties which we will be ignoring here

For $\large{\color{Purple}f: \mathbb{R} \to  \mathbb{R}}$, recall that the Taylor series is written as 

$$\Huge{\color{Purple}
f(x)\approx f(x^0)+(x-x^0)\frac{df}{dx}+\frac{1}{2}(x-x^0)^2 \frac{d^2f}{dx^2}+\cdots
}
$$

For $\large{\color{Purple}f: \mathbb{R}^n \to  \mathbb{R}}$ , the Taylor series can be  written as 

$$\Huge{\color{Purple}
f(x)\approx f(x^0)+(x-x^0)^{\top}g+\frac{1}{2}(x-x^0)^{\top}H(x-x^0)^{\top}+\dots}
$$

Here, $\large{\color{Purple} g \nabla_x f(x^0)}$  and $\large{\color{Purple}H}$ is the **Hessian** calculated at $\large{\color{Purple}x^0}$ also


## References
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* Dr Balaji, Prof IITM
* [Khan Academy](https://www.khanacademy.org/)

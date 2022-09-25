## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

#### [_Derivatives Theory_](https://github.com/iAmKankan/Mathematics/edit/main/optimization/README.md#derivatives)
   * [_Partial Derivative_](https://github.com/iAmKankan/Mathematics/edit/main/optimization/README.md#partial-derivative)
#### [_Gradien Theory_](https://github.com/iAmKankan/Mathematics/edit/main/optimization/README.md#gradient)
- Hessian
- Jacobian
- Taylor Series

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
\Huge\boxed{\nabla f= \begin{bmatrix}\frac{\partial f}{\partial x}\\
\frac{\partial f}{\partial y}
\end{bmatrix}}
\end{aligned}
}
$$

* The gradient of a scalar-valued multivariable function $\large{\color{Purple}f(x, y, \dots)}$, denoted $\large{\color{Purple}\nabla f}$, packages all its partial derivative information into a vector:

$$\Huge{\color{Purple}
\nabla f(x,y)= \begin{bmatrix} \frac{\partial f}{{\color{Green}\partial x}}\\
\frac{\partial f}{{\color{Blue}\partial y}}\\
\vdots
\end{bmatrix}
}
$$

In particular, this means $\large{\color{Purple}\nabla f}$ is a vector-valued function.
* If you imagine standing at a point $\large{\color{Purple}(x_0, y_0, \dots)}$  in the input space of $\large{\color{Purple}f}$, the vector $\large{\color{Purple}\nabla f(x_0, y_0, \dots)}$  tells you which direction you should travel to increase the value of $\large{\color{Purple}f}$ most rapidly.
* These gradient vectors— $\large{\color{Purple}\nabla f(x_0, y_0, \dots)}$ — are also perpendicular to the contour lines of $\large{\color{Purple}f}$.

#### Example #2
Suppose we ahave a curve $z=f(x,y)$ , how much does the **value of the function change** at this **point** if the value of **x** changes.
* You have partial derivative of **x** as well as of **y** - $\frac{\partial f}{\partial x}$ and $\frac{\partial f}{\partial y}$
* Instead of just looking at these two directions like -
    * $\frac{\partial f}{\partial x}$, would be the change in the direction of **x** and 
    * $\frac{\partial f}{\partial y}$, would be the change in direction of **y**.
* You could ask for the 3rd direction, I could call it as $\frac{\partial f}{\partial v}$, where **v** is some arbitrary direction okay. 
* So if this is **x**, this is **y** and **v** could be some 3rd direction altogether.

So the gradient is defined as basically a concatenation or putting together of all these partial derivative, so in this case with the two-dimensional case we have to search partial derivatives, in the n dimensional case you will have n such partial derivatives and you would basically write the gradient of F in my case would be 

$$\Huge{\color{Purple}
\nabla f(x,y)= \begin{bmatrix} \frac{\partial f}{\partial x}\\
\frac{\partial f}{\partial y}\\
\vdots
\end{bmatrix}
}
$$

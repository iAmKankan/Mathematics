## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

- Derivatives
- Gradien
- Hessian
- Jacobian
- Taylor Series

## Derivatives
In mathematics, the **derivative of a function of a real variable** measures the sensitivity to change of the **function value** (**output value 'y'** ) with respect to a change in its **argument** (**input value 'x'**)

**Derivative** typically measures _**how one quantity changes when there is a small change in another**_. _It is essential for any type of **optimisation**_.

#### Example
If you have something like ${\color{Purple}\displaystyle{\frac{dY}{dX}}}$ it means how much does ${\color{Purple}Y}$ change given that ${\color{Purple}X}$ changes buy a certain amount

### In Geometry
**Geometrically**, in **one dimension**, this can be given as the **slope** of the **tangent** and it is expressed by a **scalar** function. like-

$$\large{\color{Purple} 
\boxed{f^\prime(a)}=\boxed{\frac{df}{dx}(x=a)} =\boxed{ \lim_{h\to 0}\frac{f(x+h)-f(x)}{h}}
}
$$

In **higher dimensions**, it simply mean you still have a **scalar function** but **X** now is a vector ${\color{Purple}\mathbf{\vec{X}}}$. 
* So in that case, ${\color{Purple}\mathbf{\vec{X}}}$ could be something like let us say ${\color{Purple}\mathbf{\vec{X}= (X_1, X_2, X_3); \vec{X}\in} \mathbb{R}^3}$, or 
* It could be ${\color{Purple}\mathbf{\vec{X}= (X_1, X_2); \vec{X}\in} \mathbb{R}^2}$,
* So in such a case we can have partial derivative, so let us look at such an example let us say ${\color{Purple}\mathbf{Z = F( X , Y)}}$

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/185729977-fb75f65b-c829-4e3c-9011-778e66fa4614.png" width=25% />
    <img src="https://user-images.githubusercontent.com/12748752/191807903-de529575-ea90-4427-bfb7-1c00bb187e2e.png" width=30%/>
  <img src="https://user-images.githubusercontent.com/12748752/185731247-dd55fb41-9147-4d1c-88a6-b3501efc15d4.png" width=25% />
</p>




In the left side, if this is the **curve** $\large {\color{Purple} y = f(x)}$ and a point let us say $\large {\color{Purple} p}$, if we differentiate $\large {\color{Purple} y}$ with respect to $\large {\color{Purple} x}$ at $\large {\color{Purple} x\ = \ p}$ we will get the **slope** of the **tangent**. 

#### We can denote this as-
* **_`dy`_ by _`dx`_ at _`x`_ equal to `p` $\large{\color{Purple}\displaystyle{\frac{dy}{dx}[x = p]}}$ or $\LARGE{\color{Purple}\left.{\frac {dy}{dx}}\right|_{x=p}}$ or**
* **_`f`_ prime _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (p)}}$ or  _`f`_ prime _`x`_ equals _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (x = p)}}$**


#### The equation
$$\large{\color{Purple}\displaystyle{f^\prime (a)=\frac{\mathrm{d} f}{\mathrm{d} x}(x=a)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}}}$$

`x + h – f(x)`  by `h`, this of course is the limits of this secants, as they go towards this point and become a **tangent**, so the slope at this point `x` and `x + h`, so we find out the difference in values and as this limit tends to `0`, **the slope** will tend to a **finite value** and that is what we call **_the derivative of the slope at that point_**.

Now, If we have higher dimensions, by higher dimensions I simply mean we still have a **scalar function** but **x** now is a vector. So in that case, $\large {\color{Purple} \vec{x}}$  could be something like let us say $\large {\color{Purple} \vec{x}=(x_1, x_2, x_3)}$ and $\large {\color{Purple} x \in \mathbb{R}^3}$ or the figure that I will show shortly could be $\large {\color{Purple} \vec{x}=(x_1, x_2)}$  which means $\large {\color{Purple} x \in \mathbb{R}^2}$ .

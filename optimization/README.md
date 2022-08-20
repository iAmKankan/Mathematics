## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

- Derivatives
- Gradien
- Hessian
- Jacobian
- Taylor Series

## Derivatives
**Derivatives** typically measure _how one quantity changes_ when there is _a small change in another_.
#### Example
If you have something like ${\color{Purple}\displaystyle{\frac{dy}{dx}}}$ it means how much does ${\color{Purple}y}$ change given that ${\color{Purple}x}$ changes buy a certain amount

### In Geometry
<img src="https://user-images.githubusercontent.com/12748752/185729977-fb75f65b-c829-4e3c-9011-778e66fa4614.png" width=20% />

**Geometrically** in a simple **scalar** case we look at this as the slope of a **tangent**.

So if this is the curve $\large {\color{Purple} y = f(x)}$ and if this is the point let us say $\large {\color{Purple} p}$, if we differentiate $\large {\color{Purple} y}$ with respect to $\large {\color{Purple} x}$ at $\large {\color{Purple} x\ equal\ to\ p}$ we will get the slope of this tangent, 

#### We can denote this as-
* **_`dy`_ by _`dx`_ at _`x`_ equal to `p` $\large{\color{Purple}\displaystyle{\frac{dy}{dx}[x = p]}}$ or $\LARGE{\color{Purple}\left.{\frac {dy}{dx}}\right|_{x=p}}$ or**
* **_`f`_ prime _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (p)}}$ or  _`f`_ prime _`x`_ equals _`p`_ $\large{\color{Purple}\displaystyle{f^\prime (x = p)}}$**

<img src="https://user-images.githubusercontent.com/12748752/185731247-dd55fb41-9147-4d1c-88a6-b3501efc15d4.png" width=20% align="right"/>

#### The equation
$$\large{\color{Purple}\displaystyle{f^\prime (a)=\frac{\mathrm{d} f}{\mathrm{d} x}(x=a)=\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}}}$$

`x + h – f(x)`  by `h`, this of course is the limits of this secants, as they go towards this point and become a **tangent**, so the slope at this point `x` and `x + h`, so we find out the difference in values and as this limit tends to `0`, **the slope** will tend to a **finite value** and that is what we call **_the derivative of the slope at that point_**.

Now, If we have higher dimensions, by higher dimensions I simply mean we still have a **scalar function** but **x** now is a vector. So in that case, $\large {\color{Purple} \vec{x}}$  could be something like let us say $\large {\color{Purple} \vec{x}=(x_1, x_2, x_3)}$ and $\large {\color{Purple} x \in \mathbb{R}^3}$ or the figure that I will show shortly could be $\large {\color{Purple} \vec{x}=(x_1, x_2)}$  which means $\large {\color{Purple} x \in \mathbb{R}^2}$ .

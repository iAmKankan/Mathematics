## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## Why we need Numerical Optimization?
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/193400409-b4e4ab7a-1795-416f-9514-15f615d02568.png" width=30%/>
</p>

Suppose we have function $\large{\color{Purple} f(x)}$ and let us say $\large{\color{Purple} \vec{x}}$ is a vector and has two components $\large{\color{Purple} x_1}$ and $\large{\color{Purple} x_2}$ . 
* In that case if you knew $\large{\color{Purple} f(x)}$ as an **analytical function** of $\large{\color{Purple} x_1}$ and $\large{\color{Purple} x_2}$, then you could use various ideas such as setting **gradient** of $\large{\color{Purple} f=0}$ and you have standard methodologies to find out what the appropriate **minimum** or **maximum** is.

But, most of the cases we do not have explicit expressions. So you do not really know what $\large{\color{Purple} f}$ is, so an **explicit expression** would be something like this- $\large{\color{Purple}J(w )=𝑤_1^2+𝑤_2^2+𝑤_3^2+4 }$. In this case some $\large{\color{Purple} w}$ comes in and some $\large{\color{Purple} J}$ comes out you do not really know analytical expression is unknown.

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/201783660-f19577c4-8b82-4ffd-9178-8c40314f7e56.png" width=30%/>
</p>

So in this case in the case of deep learning this black box is typically a neural network or something of that sort. So what we want to find out something that can deal directly with numbers rather than with analytical expressions and that is why you need numerical optimization as against analytical optimization.


### Iterative optimization
* We want to drive the gradient $\large{\color{Purple}{\nabla}_𝑤 𝐽 \ldots \ldots \ldots\[ j: function; w: variables \]}$ of the function that you are trying to minimize or maximize to  $\large{\color{Purple}\vec 0}$ .

#### Iterative Process:
* Guess for $\large{\color{Purple} w}$ (which is the optimum)
* Run through the **black box** and find out the Gradient of $\large{\color{Purple} w}$ or $\large{\color{Purple} J(w)}$
* Find $\large{\color{Purple}{\nabla}_𝑤 𝐽 }$ 
* If $\large{\color{Purple}{\nabla}_𝑤 𝐽 = 0}$ , we stop, else we need to take a new guess 
   * More precisely, improve our guess 
* A very common method for **improving the guess** is called <ins><b><i>Gradient Descent</i></b></ins>.


### Gradient Descent in a simple Scalar Case
* Where $\large{\color{Purple} J(w)}$, $\large{\color{Purple} w}$ is not a vector rather a scalar.
* Our task is to improve our guess for $\large{\color{Purple} w}$ such that we move from a region of higher gradient to a region of lower gradient
<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/205314260-17e72cf7-8529-4659-8bfc-58b961209655.png" width=40% />
</p>

* If we have a new guess $\large{\color{Purple} w^{(1)}}$, and obhously it is not optimum Because at point  $\large{\color{Purple} J( w^{(1)})}$,  $\large{\color{Purple}\frac{\mathrm{d}J }{\mathrm{d} w}  \neq 0 }$
* At This point  $\large{\color{Purple} w^{(1)}}$ we have option to go either left or right. Here we would like to go left. Why?
* The Slope of $\large{\color{Purple} J( w^{(1)})}$ is positive or $\large{\color{Purple} J( w^{(1)})> 0}$, So we can say the optimum $\large{\color{Purple} w^{*}}$ lies some where here.
* For scalar (i.e. one component) $\large{\color{Purple} w}$, this is easy

$$ \large{\color{Purple}
w^{new}= w^{old}-\alpha \left( \frac{\mathrm{d}J }{\mathrm{d} w} \right)
}
\left [ \textrm{Where }\alpha \textrm{ is a positive arbitrary parameter or learning rate} \right ]
$$



![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

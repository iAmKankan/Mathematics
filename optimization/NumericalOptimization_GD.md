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
* We want to drive the gradient $\large{\color{Purple}{\nabla}_𝑤 𝐽 \ldots \ldots \ldots\[ j: function; w: variables \]}$ of the function that you are trying to minimize or maximize to  $\large{\color{Purple}0}$ .

#### Iterative Process:
* Guess for $\large{\color{Purple} w}$
* Run through the **black box** and find value of $\large{\color{Purple} J(w)}$




![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

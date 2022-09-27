## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* **The basic idea behind much of Machine learning is to build models that *map input data* to *output data*.**
* **We derive parameters of these models based on “training” on some given data.**
* **We can see the whole of machine learning as a process that finds the best/optimal Model for the given data.**
* **Most machine learning problems are, therefore, ultimately optimization problems**

#### The general optimization task is to *maximize* or *minimize* a function $\Large{\color{Purple}𝑓(\mathbf{x})}$ by varying $\Large{\color{Purple}\mathbf{x}}$. The function can do something like takes in a vector and sends out a scalar $\Huge{\color{Purple}𝑓: \mathbb{R}^n \to \mathbb{R}}$,
* The function $\large{\color{Purple}𝑓(\mathbf{x})}$ is called the $\large{\color{Red}\textrm{ objective function }}$ or $\large{\color{Red}\textrm{ cost function }}$ or $\large{\color{Red}\textrm{ loss function}}$.
* The function $\large{\color{Purple}𝑓(\mathbf{x})}$ maybe a scalar (single objective) or a vector (multi-objective).
* In this course (and most of Machine Learning) we deal only with a single objective. That is, $\large{\color{Purple}𝑓(\mathbf{x})}$ is a scalar.
* However, $\large{\color{Purple}\mathbf{x}}$ is, in general, a vector.
* Therefore, $\large{\color{Purple}𝑓: \mathbb{R}^n \to \mathbb{R}}$
* For example, $\large{\color{Purple} 𝑓(𝑥_1,𝑥_2,𝑥_3 )=𝑥_1^2+𝑥_2^2+𝑥_3^2}$ . Here, $\large{\color{Purple}𝑓: \mathbb{R}^3 \to \mathbb{R}}$

#### It is possible to reduce all optimization problems to minimization problems.
* That is, all problems can be written as find $\large{\color{Purple}\mathbf{x}}$  that minimizes $\Large{\color{Purple}𝑓(\mathbf{x})}$
* Any maximization problem can be written as minimization of - $\large{\color{Purple}𝑓(\mathbf{x})}$ 

We denote the optimal or minimal solution to the problem as $\large{\color{Purple}\mathbf{x}^∗ =arg⁡ min⁡ 𝑓(\mathbf{x})}$ . Now the meaning of $\large min f(x) =$ minimum value of x, $\large argmin f(x) =$ That x which result in min f. 

## Optimization Scalar
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192631688-9b935c80-a105-4bb1-a687-d97b0833b52a.png" width=30%/>
</p>

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

## Optimization Scalar x
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/192631688-9b935c80-a105-4bb1-a687-d97b0833b52a.png" width=30%/>
  <img src="https://user-images.githubusercontent.com/12748752/193223853-07959a04-b55c-4e2b-8454-3b2041eb5b8e.png" width=20% align="center"/>
  <img src="https://user-images.githubusercontent.com/12748752/193222538-cfdd8b41-201b-4ca1-8392-3ea0196626c0.png" width=10%/>
  <img src="https://user-images.githubusercontent.com/12748752/193222615-9829db20-47bd-4f64-aa3a-d0b219370584.png" width=20%/>
</p>

* We will look at the $\large{\color{Red}\textrm{unconstrained problem} }$ ( $\large{\color{Purple}x }$ can go from $\large{\color{Purple} \mathbf{-\infty} \to \mathbf{+\infty} }$ ). That is, find $\large{\color{Purple}x }$ that minimizes $\large{\color{Purple}𝑓(𝑥)}$ with $\large{\color{Purple}x \in \mathbb{R}}$ . That is, no constraints on $\large{\color{Purple}x }$.
* It can be shown that any local extremum will have the property $\large{\color{Purple}𝑓^\prime (𝑥)=0 }$
   * Such points are called $\large{\color{Red}\textrm{ stationary points } }$ or $\large{\color{Red}\textrm{ critical points} }$. 
   * The stationary point may be a (local) minimum, maximum or saddle point

* If $\large{\color{Purple}{f}\'\' (𝑥)>0}$ , it is a **local minimum**
* If $\large{\color{Purple}{f}\'\' (𝑥)<0}$ , it is a **local maximum**
* If $\large{\color{Purple}{f}\'\' (𝑥)=0}$ , it could be a **saddle point**
* The absolute **lowest/highest level** of $\large{\color{Purple}𝑓(𝑥)}$ is called the **global maximum/minimum**


## Optimization – Multivariate x
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* In this case the unconstrained optimization problem is to find $\large{\color{Purple}x }$  that minimizes $\large{\color{Purple}𝑓(𝑥)}$ with $\large{\color{Purple}x \in \mathbb{R}^n}$. That is, there are no constraints on $\large{\color{Purple}x }$.

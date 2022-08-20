## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

#### Every single thing that a machine learning algorithm does maps one set of numbers to another set of numbers.

## Linear Regression
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

<img src="https://user-images.githubusercontent.com/12748752/185733992-10bdd718-70b7-4375-a26d-3ee484a8454e.png" width=60%/>

Given some input vector $\large{\color{Purple}\vec{\mathbf{v}}}$, if you want to connect it to some output vector $\large{\color{Purple}\vec{\mathbf{y}}}$ via a linear model, for some reason you think that the connection between input and output, the regression connection is actually through a linearity connection. In that case let us say our $\large{\color{Purple}h(x)}$ with parameters $\large{\color{Purple}w}$ is assumed to be a linear model, in that case all you do is you take a hypothesis function $\large{\color{Purple}h(x)}$, you say that my guess is $\large{\color{Purple}\hat{\mathbf{y}}}$, you will have already got some ground truth $\large{\color{Purple}\hat{\mathbf{y}}}$ and using these two you calculate the cost function $\large{\color{Purple}\mathrm{J}}$ and you feed it back so as to improve w ok by looking at $\huge {\color{Purple} \frac{\partial J }{\partial w}}$ .

### Linear  regression <img src="https://user-images.githubusercontent.com/12748752/185735909-33c47ed4-affa-486e-89e0-353ca7e0c9a7.png" width=60% align="center"/>

* In linear regression you have $\large{\color{Purple} \vec{x}}$, you multiply by $\large{\color{Purple} w}$ and run it through a summation $\large{\color{Purple} \sum }$ and you get $\large{\color{Purple} \hat{y}}$, this is linear regression.

### logistic  regression <img src="https://user-images.githubusercontent.com/12748752/185735906-6b3d9fe7-ee91-4e53-9abd-43c2b8fe95ef.png" width=60% align="center"/>

### Neural net flow <img src="https://user-images.githubusercontent.com/12748752/185735910-f1f42ebb-aeb1-4009-9391-e2a6c3e641af.png" width=80% align="center"/>
* More than a layer is called Deep network.

### Important notes
* how do we characterize the output y or ^y.
* Next is of course what is the feed forward model
* The 3rd thing is what is the loss function **J**
* Fourth, what you have to find out is how do we calculate $\large{\color{Purple} \frac{\partial J}{\partial w}}$ ? in other words this is the **gradient problem**
* There is a 5th problem which will not be discussing very much which is how do we use $\large{\color{Purple} \frac{\partial J}{\partial w}}$ to find better **w**, **Optimization problem**.


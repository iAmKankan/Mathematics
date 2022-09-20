## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## RECAP of Derivative and limit

#### ◾ Velocity meaning and its formula
The velocity of a moving particle is the distance travelled by it in unit time in a given direction, or in other words, velocity is the **rate of displacement of a body**.


$$\large{\color{Purple}
\boxed{Velocity\ = \frac{displacement}{time \ taken}}
}
$$

#### Types of velocity
* **Uniform velocity**
* **Variable velocity or non-uniform velocity**
* ◾ **Average velocity**
Consider a body moving with variable velocity. Then the ratio of total displacement to the total time interval is called average velocity.

$$\large{\color{Purple}
\boxed{Average Velocity\ = \frac{Total\ displacement}{Total\ time \ taken}}
}
$$

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/190564917-d9f9e3bc-2a0a-4af2-863c-27e9326678ea.png" width=40% />
</p>


* ◾ **Instantaneous velocity**
Consider a body moving with variable velocity. The velocity of an object at **a particular instant of time** is called its instantaneous velocity.
For an object in motion along the **X –direction**, let **x(t)** and **x(t + Δt)** be the position co-ordinates at times **t**  and **(t + Δt)** respectively. 

Then its average velocity during the

$$\large{\color{Purple}
\begin{align*}
& v_{avg}\ = \frac{x(t + \Delta t) -x(t)}{(t + \Delta t) -t}\\ 
& v_{avg}\ = \frac{\Delta x}{\Delta t}
\end{align*}
}
$$

Then the instantaneous velocity is given by


$$\large{\color{Purple}
\begin{align*}
& v_{inst}\ ,\ \bar{v}= \lim_{\Delta t \to 0} \Big\( \frac{\Delta x}{\Delta t} \Big\)\\
 &\Huge \boxed{v_{inst}\ ,\ \bar{v}= \frac{d x}{d t}} \\
\end{align*}
}
$$

where **Δx** be the displacement of a body in an infinitely **small interval** of time **Δt**.

Here the time **Δt** tends to zero in the limit (because **&Delta;t** is very small that's why **&Delta;t &rarr; 0**). The direction of instantaneous velocity is along the tangent to the path at the point.
Also, $\large \mathbf{\frac{dx}{dt}}$ is the derivative of **x** with respect to time **t**. In other words, the velocity of a particle at any instant is the derivative of the position co-ordinate of the particle with respect to time.


<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/190576878-fbbe0afd-15e4-431a-8546-d5e2ec443f5e.png" width=60% />
</p>


#### ◾ Now If we want to find out the *Instantaneous velocity* of a point let say **p**
* Then we need to make a **tangent** on this point.
* Find out the **slope** of the **tangent**
* The **slope** of a tangent is $\large{\color{Purple} \ \ tan \theta\ \ \ or\ \ \  \frac{Perpendicular}{Base}}$
* And that becomes the value of **Instantaneous velocity**.

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/190583668-08931f91-2431-4a0e-a3e5-6e99357a7bad.png" width=30% />
</p>

### ◾ Derivative is slope of a tangent 
* Derivative of a function at a point **P** exist, if and only if the **function is continous** at point **P**.

## Continuity and Differentiability
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

### Continuity Function
◼️ **Definition 1:**  Suppose **_f_** is a real function on a subset of the real numbers and let **_c_** be a point in the domain of **_f_**. Then **_f_** is continuous at **c** if
* Perticular point.

$$\large{\color{Purple}
\boxed{\lim_{x \to c} f(x ) = f(c)}
}
$$

◼️ **Definition 2:**  A real function **f** is said to be continuous if it is continuous at every point in the domain of **f**.

### ◼️ Algebra of continuous functions
◼️ **f** and **g** be two real functions continuous at a real number **c**

* f+g is continuous at x = c
* f-g is continuous at x = c
* f.g is continuous at x = c
* f/g is continuous at x = c,(provided g (c) &ne; 0)

◼️ If at a point **c**, **x²** is continuous and if **g(x²)** i.e. **sin(x2)** is continuous, then **sin(x2)** is continuous at **x = c**

## Differentiability
In mathematics, a differentiable function of one real variable **is a function whose derivative exists at each point in its domain**.

Suppose **f** is a real function and **c** is a point in its domain. The derivative of **f** at **c** is defined by

$$\large{\color{Purple}
f^\prime(c) = \lim_{h \to 0} =\frac{f(c+h)-f(c)}{h}
}
$$

* First findout the value of **f(c+h)** and **f(c)**.
* Then subtract it and finally divide it by **h**.
* It al so convays that the value of **c** and **c+h** are very close coz **h &rarr; 0** 

####  If we can find the _derivative_ exist of a function then the function is _differentiable_.


<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/190884038-e6e24cee-08d3-446b-a12e-fd24865f0a3c.png" width=60% />
</p>


* Derivative of **_f_** is denoted by **_f&prime;(x)_** or $\large{\color{Purple} \frac{d}{dx}(f(x))}$

* Derivative of **f** at **c** is denoted by $\large{\color{Purple} \frac{d}{dx}(f(x))|_c}$ or **_f&prime;(c)_** 

* Every **differentiable** function is **continuous**.
* A function is not differentiable at a point if: -The function is not continuous at the point.
* A function is not differentiable at a point if: -The graph has a vertical line at the point
  * **&theta;** means **90&deg;**,  **tan90&deg; = Undefined** (if we cant calculate **hypotenious/base** then the result would be **Undefined**)


### Derivative of Standard Function
#### Rules

1) **(u&pm;v)&prime; = u&prime; &pm; v&prime;**
2) **(uv)&prime; = u&prime;v + uv&prime;** [**Product rule**] or $\large{\color{Purple} \frac{d}{dx}(uv) = \Big\( \frac{d}{dx}\Big\)v + u\Big\(\frac{d}{dx}\Big\)}$
3) $\large{\color{Purple} \Big\(\frac{u}{v}\Big\)^\prime = \frac{u^\prime v - uv^\prime}{v^2} ;v \neq 0  }$ (Quotient rule)

### Derivative of Composite Functions
Composite means made of several parts 
* **f(x)=sin(x<sup>2</sup>)** 
   * Let **x<sup>2</sup> = t** So, **f(x) = sin t**, where **t** is another function

* **f(x) = (2x+3)<sup>3</sup>**
   * **Let 2x + 3 = t** So, **f(x) = t<sup>3</sup>** , where **t** is another function

#### Chain rule
* **f(x)=sin(cos(x<sup>2</sup>))** For this kind of **composite function** we use **chain rule** to findout its **derivative**.


#### Explicit and Implicit Function
It is not necessary that functions are always expressed in this form **_y=f(x)_** . For example, consider one of the following relationships between x and y:
1) $\large x - y - \pi = 0$
2) $\large x + \sin{xy} - y = 0$

* In the first case, we can solve for y and rewrite the relationship as **y = x - &pi;**.
* In the second case, it does not seem that there is an easy way to solve for **y**. Nevertheless, there is no doubt about the dependence of **y** on **x** in either of the cases. 
* When a relationship between **x** and **y** is expressed in a way that it is easy to solve for y and write **y = f (x)**, we say that **y** is given as an **explicit function** of **x**.
* In the latter case it is **implicit** that **y** is a function of **x** and we say that the relationship of the second type, above, gives function implicitly. In this subsection, we learn to differentiate implicit functions.

#### Derivative of Implicit Function
Differentiate the complete expression with respect to a given variable. 

#### *Exercise:* 
1) Find $\frac{dy}{dx} \textrm{if x - y =} \pi.$

### Derivatives of inverse trigonometric functions

$$\large{\color{Purple}
\begin{align*}
& \boxed{\Huge f(x) \sin^{-1}x }\\
& \textrm{Let } y = \sin^{-1}x\\
& x = \sin y\\
&\textrm{Now Differentiate with respect to } x\\
& dx/dx = \cos y\ dy/dx
\end{align*}
}
$$


###  Logarithmic and Exponential Functions
#### Exponential function
**y = b<sup>x</sup>** Exponential function with positive base **b> 1** is the function.

<p align="center">
  <img src="https://user-images.githubusercontent.com/12748752/191160758-e4612bf8-14bf-4654-9008-61e9d666fa1f.png" width=30%/> 
  <img src="https://user-images.githubusercontent.com/12748752/191161144-76086df8-9e4b-406b-ab90-8b913a46f226.png" width=30%/> 
</p>            



* Domain could be anything (x is -ve or +ve)
* Range is always +ve real numbers.
#### 2 types exponential functions
  1) Common exponential functions $y=10^x$ Base 10
  2) Natural exponential functions $y=e^x$ base e


#### e: exponential constant (Euler's constant)

* Value **e= 2.718** (approx)
#### How to express
* $\large e = \lim_{x \to \infty}  (1 + \frac{1}{x} )^x = 2 =2.718281828459\cdots $
* $\large e = \lim_{x \to 0}  (1 + x )^\frac{1}{x} $
* etc

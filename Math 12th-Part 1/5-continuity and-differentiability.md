## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## RECAP of Derivative and limit
#### [_Derivatives Theory_](https://github.com/iAmKankan/Mathematics/tree/main/optimization/README.md#derivatives)
   * [_Partial Derivative_](https://github.com/iAmKankan/Mathematics/tree/main/optimization/README.md#partial-derivative)
   
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

### Logarithmic and Exponential Functions
We can write any exponential function in the form of log

**Logarithmic Functions:** Let **b> 1** be a real number. Then we say **log<sub>b</sub>a = x** if **b<sup>x</sup>= a** (**Logarithm** of **a** to base **b**)
#### Example:
1) **2<sup>4</sup>=16** **&rArr;** **log<sub>2</sub>16 = 4**
2) **10<sup>3</sup>=1000** &rArr; **log<sub>10</sub>1000 = 3**

#### Properties of log
1) **Change of Base rule**
    * ***Example:***
       *  $\large\log_ap = \frac{\log_bp}{\log_ba}$       
2) If we have **log<sub>b</sub>pq** = **log<sub>b</sub>p** + **log<sub>b</sub>q** ( provided everyone having same base)
    * ***Example:*** 
       *  **log<sub>b</sub>p<sup>2</sup>** = **log<sub>b</sub>p** + **log<sub>b</sub>p** = **2logp**
       *  **log<sub>b</sub>p<sup>n</sup>** = **nlogp**

3) $\large{\color{Purple}\log_b \frac{p}{q} = \log_bp- \log_bq}$ ( provided everyone having same base)


### Derivative of Logarithm & Exponential functions
Formulas-
1) $\Huge{\color{Purple} \frac{d}{dx}(e^x)=e^x }$
2) $\Huge{\color{Purple} \frac{d}{dx}(\log x)=\frac{1}{x}}$

#### Logarithmic Differentiation
In this section, we will learn to differentiate certain special class of functions given in the form $\large {\color{Purple} y = f (x) = [u(x)]^{v (x)}}$
* By taking logarithm (to base e) the above may be rewritten as $\large {\color{Purple} \log y = v(x) log [u(x)]}$
* Using chain rule we may differentiate this to get $\large {\color{Purple} \frac{1}{y}.\frac{dy}{dx}= v(x). \frac{1}{u(x)}.u^\prime(x)+v^\prime(x).\log[u(x)]}$
* Which implies that $\large {\color{Purple}\frac{dy}{dx}= y \Big \[ \frac{v(x)}{u(x)}.u^\prime(x)+v^\prime(x).\log[u(x)] \Big \]}$

The main point to be noted in this method is that **f (x)** and **u(x)** must always be positive as otherwise their logarithms are not defined. This process of differentiation is known as logarithms differentiation and is illustrated by the following examples:


### Derivative of Functions in Parametric Forms
Sometimes the relation between two variables is neither explicit nor implicit, but some link of a third variable with each of the two variables, separately, establishes a relation between the first two variables. In such a situation, we say that the relation between them is expressed via a third variable. The third variable is called the parameter. More precisely, a relation expressed between two variables **x** and **y** in the form **x = f (t)**, **y = g (t)** is said to be parametric form with **t** as a parameter

### Second Order Derivatives
So far we were dealing with  **1<sup>st</sup> order derivatives** where finding out 
* the **Instantaneous velocity** in $\large\boxed{Velocity=\frac{dx}{dt}}$ and 
*  the **acceleration** in $\large\boxed{Acceleration=\frac{dv}{dt}}$
*  But the displacement is missing; $\large v=\frac{dx}{dt}$ so Acceleration is now $\large =\frac{d}{dt} \frac{dx}{dt}$
*  **or** $\boxed{Acceleration=\frac{dv}{dt} = \frac{d^2x}{dt^2} }$ that is the 2nd orger derivative

In other words, let say we have a function **_y=f(x)_** if we differentiate it we get the **1<sup>st</sup> order derivative** which is  $\large\boxed{\frac{dy}{dx}=f^\prime(x)}$  if we further differentiate it we get the **2<sup>nd</sup> order derivative** 
$\large\boxed{\frac{d}{dx}\Big \( \frac{dy}{dx}\Big\) =\frac{d^2y}{dx^2}= {f}\'\'(x)}$ 

**2<sup>nd</sup> order derivative** denoted by -

$$\Huge{\color{Purple}
\begin{matrix}
& D^2y &\normalsize or &  {y}\'\' &\normalsize or &  \Huge\frac{d^2y}{dx^2}
\end{matrix}
}
$$

Or

* Let **_y = f (x)_**.
* Then $\large\frac{dy}{dx} = f^\prime(x) \cdots \cdots (1)$ 
* If **_f&prime;(x)_** is differentiable, we may differentiate **(1)** again w.r.t. **x**. Then, the left hand side becomes $\large\frac{d}{dy}\Big\(\frac{dx}{dx}\Big \)$ which is called the **_second order derivative_** of **_y_** w.r.t. **x** and is denoted by $\large \frac{d^2y}{dx^2}$ . 
* The second order derivative of **_f(x)_** is denoted by **_f&Prime;(x)_**.

### Rolle’s Theorem
<p align="center">
  <img src ="https://user-images.githubusercontent.com/12748752/191438730-1bda6714-35ca-407d-9f8c-87d137ffd58e.jpg" width=40%/>
  <img src="https://user-images.githubusercontent.com/12748752/191452552-23b9e087-42d4-4b53-883e-4722677aae51.png" width=40%/>
</p>

For a function, $\large f:[a,b] \Rightarrow \mathbb{R}$, if
* ->f is continuous on a **closed interval** [a, b](A closed interval is an interval which includes all its limit points, and is denoted with square brackets)
* -> f is differentiable on a **open interval** (a, b) (An open interval does not include its endpoints, and is indicated with parentheses. For example, (0,1) means greater than 0 and less than 1. This means (0,1) = {x | 0 < x < 1}.)
* ->f (a) = f (b)
* then, there exists some ce (a, b) such that f'(c)=0

### Mean value Theorem
For a function, f:[a,b] ----> R, if

->f is continuous on [a, b] -f is differentiable on (a, b)

then, there exists some c&in;(a, b)

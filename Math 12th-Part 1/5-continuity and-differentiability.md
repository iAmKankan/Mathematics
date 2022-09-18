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






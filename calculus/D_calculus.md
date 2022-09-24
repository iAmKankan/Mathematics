## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [Differential calculus](#differential-calculus)
   * [Derivatives and Differentiation](#derivatives-and-differentiation)
   * [Partial Derivatives](#partial-derivatives)
   * [Gradients](#gradients)
   * [Chain Rule](#chain-rule)
   * [Power Rule](#power-rule)
   * [Other Formulas](#formula)


$$\large{\color{Purple}
\begin{align*}
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{1}&=&0 \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x}&=&1 \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^2}&=&\mathrm{2x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^n}&=&\mathrm{nx^{n-1}} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{2x}&=&\mathrm{2 * 1} \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1+x^2)}&=&\mathrm{0+2x=2x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1-x^2)}&=&\mathrm{0-2x=-2x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^x}&=&\mathrm{e^x* 1=e^x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^{f(x)}}&=&\mathrm{e^{f(x)}} \frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin x}&=&\mathrm{\cos x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\cos x}&=& \mathrm{-\sin x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan x}&=& \mathrm{\sec^2 x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan^{-1} x}&=& \mathrm{\frac{1}{1+x^2}}\\
\end{align*}}
$$

$$\large{\color{Purple}
\begin{aligned}
&\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\sin^{-1} x}&=& \mathrm{\frac{1}{\sqrt{1+x^2} }} \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin f(x)}&=&\mathrm{\cos f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos f(x)}&=&\mathrm{-\sin f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\left [ f(x) \right ]^n}&=& \mathrm{n\left [ f(x) \right ]^{n-1} *}\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{ f(x)} \\
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos^{-1}}x&=& -\frac{1}{\mathrm{\sqrt{1+x^2} } } \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\log}x&=& \frac{1}{x} \\ 
&\frac{\mathrm{d} }{\mathrm{d} x} \frac{1}{\mathrm{x}}&=&\mathrm{-\frac{1}{x^2}}\because \left ( \frac{1}{x}=x^{-1}\right )\mathrm{ (-1*x^{-1-1})} \\
\end{aligned}
}
$$













## What is Calculus
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* Calculus is the branch of mathematics that deals with continuous change.
* Calculus is also called infinitesimal calculus or “the calculus of infinitesimals”. 
* The meaning of classical calculus is the study of continuous change of functions.
* Most of these quantities are the functions of time such as velocity is equal to change in distance with respect to time. 
* The two major concepts of calculus are: 
   * Integrals 
   * Differentials
### Differential Calculus 
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* Differential calculus deals with the rate of change of one quantity with respect to another.
* The sighn of differentiation is _**d/d**_
* It is always done in respect to a variable or a function.
* That function / variable is written along side of the denominator _**d**_.
* And the thing to be differentiate is written alongside of the numerastor _**d**_.
* Suppose variable x is there and a is the number to be differentiate <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}a&space;}{\mathrm{d}x&space;}" title="\frac{\mathrm{d}a }{\mathrm{d}x }" align="center"/>.
* 'a','b','c','d' are considered as constants
* 'x','y','z' are considered as variables. 

<img src="https://user-images.githubusercontent.com/12748752/136690048-0678f8ad-4254-4d0f-8ba8-e09c4f22a0e0.png" width=70%>

* [**Why Delta Y/Delta X, It's Tan theta** ](https://github.com/iAmKankan/Mathematics/blob/main/trigonometry.md#tan-theta)

* **What are Delta X,Delta Y-** _**Change in X and change in Y to calculate slope.**_
> <img src="https://latex.codecogs.com/svg.image?Slope&space;=&space;\frac{f(X&plus;\Delta&space;X)-f(X)}{(X&plus;\Delta&space;X)-X}" title="Slope = \frac{f(X+\Delta X)-f(X)}{(X+\Delta X)-X}" />
* After cancelling off X and -X 
>> <img src="https://latex.codecogs.com/svg.image?Slope&space;=&space;\frac{f(X&plus;\Delta&space;X)-f(X)}{\Delta&space;X}" title="Slope = \frac{f(X+\Delta X)-f(X)}{\Delta X}" />
* Since the slope is not on a straight line  so we can say it is **NEARLY** not equals.
>> <img src="https://latex.codecogs.com/svg.image?Slope&space;\approx&space;&space;\frac{f(X&plus;\Delta&space;X)-f(X)}{\Delta&space;X}" title="Slope \approx \frac{f(X+\Delta X)-f(X)}{\Delta X}" />
* In order to calculate the slope of the curve we must take the limit where the value of X is very very small( small part of a curve line appears as a straight line)  

>> <img src="https://latex.codecogs.com/svg.image?Slope&space;=&space;\displaystyle&space;\lim_{\Delta&space;X&space;\to&space;0}&space;&space;\frac{f(X&plus;\Delta&space;X)-f(X)}{\Delta&space;X}" title="Slope = \displaystyle \lim_{\Delta X \to 0} \frac{f(X+\Delta X)-f(X)}{\Delta X}" />


### Common Rules
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
As was seen in :numref:`sec_calculus`, when computing derivatives one can oftentimes use a series of rules to reduce the computation to a few core functions.  We repeat them here for ease of reference.

> #### Derivative of constants: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}\mathbf{C}&space;=&space;0" title="\frac{d}{dx}\mathbf{C} = 0" align="center" />
> #### Derivative of linear functions:  <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}(ax)&space;=&space;a" title="\frac{d}{dx}(ax) = a" align="center" />
> #### Power rule: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}x^n&space;=&space;nx^{n-1}" title="\frac{d}{dx}x^n = nx^{n-1}" align="center" />
> #### Derivative of exponentials: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}e^x&space;=&space;e^x" title="\frac{d}{dx}e^x = e^x" align="center" />
> #### Derivative of the logarithm: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}\log(x)&space;=&space;\frac{1}{x}" title="\frac{d}{dx}\log(x) = \frac{1}{x}" align="center" />

### Derivative Rules
* If every derivative needed to be separately computed and stored in a table, differential calculus would be near impossible.  
* It is a gift of mathematics that we can generalize the above derivatives and compute more complex derivatives like finding the derivative of <img src="https://latex.codecogs.com/svg.image?f(x)&space;=&space;\log\left(1&plus;(x-1)^{10}\right)" title="f(x) = \log\left(1+(x-1)^{10}\right)" />.  
* The key to doing so is to codify what happens when we take functions and combine them in various ways, most importantly: sums, products, and compositions.

> #### Sum rule: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}\left(g(x)&space;&plus;&space;h(x)\right)&space;=&space;\frac{dg}{dx}(x)&space;&plus;&space;\frac{dh}{dx}(x)" title="\frac{d}{dx}\left(g(x) + h(x)\right) = \frac{dg}{dx}(x) + \frac{dh}{dx}(x)" />
> #### Product rule: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}\left(g(x)\cdot&space;h(x)\right)&space;=&space;g(x)\frac{dh}{dx}(x)&space;&plus;&space;\frac{dg}{dx}(x)h(x)" title="\frac{d}{dx}\left(g(x)\cdot h(x)\right) = g(x)\frac{dh}{dx}(x) + \frac{dg}{dx}(x)h(x)" />
> #### Chain rule: <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}g(h(x))&space;=&space;\frac{dg}{dh}(h(x))\cdot&space;\frac{dh}{dx}(x)" title="\frac{d}{dx}g(h(x)) = \frac{dg}{dh}(h(x))\cdot \frac{dh}{dx}(x)" />


#### Chain Rule
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Multivariate functions in deep learning are often *composite*, so we may not apply any of the above mentioned rules to differentiate these functions.
* _**Chain rule**_ enables us to differentiate composite functions.
> #### Let us first consider functions of a single variable.
> * Suppose that functions *y=f(u)* and *u=g(x)* are both differentiable, then the chain rule states that
>> <img src="https://latex.codecogs.com/svg.image?\frac{dy}{dx}\&space;=\&space;\frac{dy}{du}\&space;\frac{du}{dx}." title="\frac{dy}{dx}\ =\ \frac{dy}{du}\ \frac{du}{dx}." />

Now let us turn our attention to a more general scenario where functions have an arbitrary number of variables.Suppose that the differentiable function _**y**_ has variables _**u<sub>1</sub>, u<sub>2</sub>, ..., u<sub>m</sub>**_ where each differentiable function _**u<sub>i</sub>**_ has variables _**x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>**_.

##### Note that _**y**_ is a function of _**x<sub>1</sub>, x<sub>2</sub>, ..., x<sub>n</sub>**_.

Then the chain rule gives: <img src="https://latex.codecogs.com/svg.image?\frac{dy}{dx_i}&space;=&space;\frac{dy}{du_1}&space;\frac{du_1}{dx_i}&space;&plus;&space;\frac{dy}{du_2}&space;\frac{du_2}{dx_i}&space;&plus;&space;\cdots&space;&plus;&space;\frac{dy}{du_m}&space;\frac{du_m}{dx_i}" title="https://latex.codecogs.com/svg.image?\frac{dy}{dx_i} = \frac{dy}{du_1} \frac{du_1}{dx_i} + \frac{dy}{du_2} \frac{du_2}{dx_i} + \cdots + \frac{dy}{du_m} \frac{du_m}{dx_i}" align="center" />

for any **_i = 1, 2, ... , n._**


#### Quotient Rule
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
<img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}=\frac{(denominator&space;*&space;\frac{d}{dx}numerator)&space;&space;-&space;(numerator&space;*&space;\frac{d}{dx}denominator)}{denominator^2}&space;" title="\frac{d}{dx}=\frac{(denominator * \frac{d}{dx}numerator) - (numerator * \frac{d}{dx}denominator)}{denominator^2} " />


#### Power Rule
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Here we use the power rule in order to calculate the derivative and it’s pretty simple though.


>> <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^2}=\mathrm{2x}" title="\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^2}=\mathrm{2x}" />

>>   <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^n}=\mathrm{nx^{n-1}}" title="\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^n}=\mathrm{nx^{n-1}}" />

* The considered function f(x) is equal to x to the fifth.
> <img src="https://latex.codecogs.com/svg.image?\begin{cases}&space;&&space;\text{&space;if&space;}&space;f(x)=x^n&space;\\&space;&&space;\text{&space;then&space;}&space;f'(x)=n.x^{n-1}&space;\end{cases}&space;" title="\begin{cases} & \text{ if } f(x)=x^n \\ & \text{ then } f'(x)=n.x^{n-1} \end{cases} " />

> <img src="https://latex.codecogs.com/svg.image?\begin{cases}&space;&&space;f(x)=x^5&space;\\&space;&&space;f'(x)=5x^{(5-1)}&space;\\&space;&&space;f'(x)=5x^{4}&space;\end{cases}&space;" title="\begin{cases} & f(x)=x^5 \\ & f'(x)=5x^{(5-1)} \\ & f'(x)=5x^{4} \end{cases} " />


### Relation with Deep Learning
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In deep learning, we train models, updating them successively so that they  minimizing the loss function.
* Ultimately, what we really care about is producing a model that performs well on data that we have never seen before.
* But we can only fit the model to data that we can actually see. 
* Thus we can decompose the task of fitting models into two key concerns:
> _(i)_ **optimization:** the process of fitting our models to observed data.
> 
> _(ii)_ **generalization:** to produce models whose validity extends beyond the exact set of data examples used to train them.


###  Derivatives and Differentiation
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* In deep learning, we typically choose loss functions that are differentiable with respect to our model’s parameters.
*  Put simply, this means that for each parameter, we can determine how rapidly the loss would increase or decrease, were we to increase or decrease that parameter by an infinitesimally small amount.


* Let us familiarize ourselves with a few equivalent notations for derivatives.
* Given  y=f(x) , where  x  and  y  are the independent variable and the dependent variable of the function  f , respectively. 
> #### The following expressions are equivalent:
> <img src="https://latex.codecogs.com/svg.image?f'(x)&space;=&space;y'&space;=&space;\frac{dy}{dx}&space;=&space;\frac{df}{dx}&space;=&space;\frac{d}{dx}&space;f(x)&space;=&space;Df(x)&space;=&space;D_x&space;f(x)," title="f'(x) = y' = \frac{dy}{dx} = \frac{df}{dx} = \frac{d}{dx} f(x) = Df(x) = D_x f(x)," />

> #### We can use the following rules to differentiate common functions:
> <img src="https://latex.codecogs.com/svg.image?\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}C\&space;=\&space;0\&space;(&space;C\&space;&space;is\&space;a\&space;constant),\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}x^n\&space;=\&space;nx^{n-1}&space;\&space;(\&space;The\&space;power\&space;rule,\&space;n\&space;is\&space;any\&space;real\&space;number\&space;),\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}ln(x)=\frac{1}{x}&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}e^x\&space;=\&space;ex&space;\\" title="\\ \frac{\mathrm{d} }{\mathrm{d} x}C\ =\ 0\ ( C\ is\ a\ constant),\\\frac{\mathrm{d} }{\mathrm{d} x}x^n\ =\ nx^{n-1} \ (\ The\ power\ rule,\ n\ is\ any\ real\ number\ ),\\\frac{\mathrm{d} }{\mathrm{d} x}ln(x)=\frac{1}{x} \\\frac{\mathrm{d} }{\mathrm{d} x}e^x\ =\ ex \\" />

*  Suppose that functions  f  and  g  are both differentiable and  C  is a constant, we have the 
> 
> #### Constant multiple rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[Cf(x)]\&space;=\&space;C&space;\frac{d}{dx}&space;f(x)," title="\frac{d}{dx} [Cf(x)]\ =\ C \frac{d}{dx} f(x)," />
> 
> #### Sum rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[f(x)&space;&plus;&space;g(x)]\&space;=\&space;\frac{d}{dx}&space;f(x)&space;&plus;&space;\frac{d}{dx}&space;g(x)," title="\frac{d}{dx} [f(x) + g(x)]\ =\ \frac{d}{dx} f(x) + \frac{d}{dx} g(x)," />
> 
> #### Product rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[f(x)g(x)]\&space;=\&space;f(x)&space;\frac{d}{dx}&space;[g(x)]\&space;&plus;\&space;g(x)&space;\frac{d}{dx}&space;[f(x)]," title="\frac{d}{dx} [f(x)g(x)]\ =\ f(x) \frac{d}{dx} [g(x)]\ +\ g(x) \frac{d}{dx} [f(x)]," />
> 
> #### Quotient rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;\left[\frac{f(x)}{g(x)}\right]\&space;=\&space;\frac{g(x)&space;\frac{d}{dx}&space;[f(x)]&space;-&space;f(x)&space;\frac{d}{dx}&space;[g(x)]}{[g(x)]^2}." title="\frac{d}{dx} \left[\frac{f(x)}{g(x)}\right]\ =\ \frac{g(x) \frac{d}{dx} [f(x)] - f(x) \frac{d}{dx} [g(x)]}{[g(x)]^2}." />



### Partial Derivatives
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* So far we have dealt with the differentiation of functions of just one variable.
* In deep learning, functions often depend on many variables. 
* Thus, we need to extend the ideas of differentiation to these multivariate functions.
> #### Let <img src="https://latex.codecogs.com/svg.image?y&space;=&space;f(x_1,&space;x_2,&space;\ldots,&space;x_n)" title="y = f(x_1, x_2, \ldots, x_n)" />  be a function with n variables. The *partial derivative* of y with respect to its <img src="https://latex.codecogs.com/svg.image?i^\mathrm{th}\&space;&space;parameter\&space;x_i" title="i^\mathrm{th}\ parameter\ x_i" /> is
> <img src="https://latex.codecogs.com/svg.image?&space;\frac{\partial&space;y}{\partial&space;x_i}\&space;=\&space;\lim_{h&space;\rightarrow&space;0}&space;\frac{f(x_1,&space;\ldots,&space;x_{i-1},&space;x_i&plus;h,&space;x_{i&plus;1},&space;\ldots,&space;x_n)&space;-&space;f(x_1,&space;\ldots,&space;x_i,&space;\ldots,&space;x_n)}{h}." title=" \frac{\partial y}{\partial x_i}\ =\ \lim_{h \rightarrow 0} \frac{f(x_1, \ldots, x_{i-1}, x_i+h, x_{i+1}, \ldots, x_n) - f(x_1, \ldots, x_i, \ldots, x_n)}{h}." />
>
* To calculate <img src="https://latex.codecogs.com/svg.image?&space;\frac{\partial&space;y}{\partial&space;x_i}\&space;" title=" \frac{\partial y}{\partial x_i}\ " />, we can simply treat <img src="https://latex.codecogs.com/svg.image?x_1,&space;\ldots,&space;x_{i-1},&space;x_{i&plus;1},&space;\ldots,&space;x_n" title="x_1, \ldots, x_{i-1}, x_{i+1}, \ldots, x_n" /> as constants and calculate the derivative of y with respect to <img src="https://latex.codecogs.com/svg.image?x_i" title="x_i" />. 
> <img src="https://latex.codecogs.com/svg.image?\frac{\partial&space;y}{\partial&space;x_i}\&space;=\&space;\frac{\partial&space;f}{\partial&space;x_i}\&space;=\&space;f_{x_i}\&space;=\&space;f_i\&space;=\&space;D_i&space;f\&space;=\&space;D_{x_i}&space;f." title="\frac{\partial y}{\partial x_i}\ =\ \frac{\partial f}{\partial x_i}\ =\ f_{x_i}\ =\ f_i\ =\ D_i f\ =\ D_{x_i} f." />

### Gradients
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* We can concatenate partial derivatives of a multivariate function with respect to all its variables to obtain the gradient vector of the function. 
* Suppose that the input of function  <img src="https://latex.codecogs.com/svg.image?f:&space;\mathbb{R}^n\to&space;\mathbb{R}" title="f: \mathbb{R}^n\to \mathbb{R}" />  is an  n -dimensional vector <img src="https://latex.codecogs.com/svg.image?x=[x_1,x_2,\ldots,x_n]^T" title="x=[x_1,x_2,\ldots,x_n]^T" />  and the output is a scalar. The gradient of the function  f(x)  with respect to  x  is a vector of  n  partial derivatives:
> <img src="https://latex.codecogs.com/svg.image?\nabla_{\mathbf{x}}&space;f(\mathbf{x})&space;=&space;\bigg[\frac{\partial&space;f(\mathbf{x})}{\partial&space;x_1},&space;\frac{\partial&space;f(\mathbf{x})}{\partial&space;x_2},&space;\ldots,&space;\frac{\partial&space;f(\mathbf{x})}{\partial&space;x_n}\bigg]^\top," title="\nabla_{\mathbf{x}} f(\mathbf{x}) = \bigg[\frac{\partial f(\mathbf{x})}{\partial x_1}, \frac{\partial f(\mathbf{x})}{\partial x_2}, \ldots, \frac{\partial f(\mathbf{x})}{\partial x_n}\bigg]^\top," />

> <img src="https://latex.codecogs.com/svg.image?\\\mathrm{Where\&space;\nabla_{\mathbf{x}}\&space;f(\mathbf{x})\&space;is\&space;often\&space;replaced\&space;by\&space;\nabla\&space;f(\mathbf{x})\&space;when\&space;there\&space;is\&space;no\&space;ambiguity.}\\\mathrm{Let\&space;\mathbf{x}\&space;be\&space;an\&space;'n'\&space;-dimensional\&space;vector,\&space;the\&space;following\&space;rules\&space;are\&space;often\&space;used\&space;when\&space;differentiating\&space;multivariate\&space;functions:}\\&space;" title="\\\mathrm{Where\ \nabla_{\mathbf{x}}\ f(\mathbf{x})\ is\ often\ replaced\ by\ \nabla\ f(\mathbf{x})\ when\ there\ is\ no\ ambiguity.}\\\mathrm{Let\ \mathbf{x}\ be\ an\ 'n'\ -dimensional\ vector,\ the\ following\ rules\ are\ often\ used\ when\ differentiating\ multivariate\ functions:}\\ " />
>> <img src="https://latex.codecogs.com/svg.image?\\For\&space;all\&space;\mathbf{A}&space;\in&space;\mathbb{R}^{m&space;\times&space;n},&space;\nabla_{\mathbf{x}}&space;\mathbf{A}&space;\mathbf{x}&space;=&space;\mathbf{A}^\top,\\For\&space;all\&space;&space;\mathbf{A}&space;\in&space;\mathbb{R}^{n&space;\times&space;m},&space;\nabla_{\mathbf{x}}&space;\mathbf{x}^\top&space;\mathbf{A}&space;&space;=&space;\mathbf{A},\\For\&space;all\&space;&space;\mathbf{A}&space;\in&space;\mathbb{R}^{n&space;\times&space;n},&space;\nabla_{\mathbf{x}}&space;\mathbf{x}^\top&space;\mathbf{A}&space;\mathbf{x}&space;&space;=&space;(\mathbf{A}&space;&plus;&space;\mathbf{A}^\top)\mathbf{x},\\\nabla_{\mathbf{x}}&space;\|\mathbf{x}&space;\|^2&space;=&space;\nabla_{\mathbf{x}}&space;\mathbf{x}^\top&space;\mathbf{x}&space;=&space;2\mathbf{x}.\\" title="\\For\ all\ \mathbf{A} \in \mathbb{R}^{m \times n}, \nabla_{\mathbf{x}} \mathbf{A} \mathbf{x} = \mathbf{A}^\top,\\For\ all\ \mathbf{A} \in \mathbb{R}^{n \times m}, \nabla_{\mathbf{x}} \mathbf{x}^\top \mathbf{A} = \mathbf{A},\\For\ all\ \mathbf{A} \in \mathbb{R}^{n \times n}, \nabla_{\mathbf{x}} \mathbf{x}^\top \mathbf{A} \mathbf{x} = (\mathbf{A} + \mathbf{A}^\top)\mathbf{x},\\\nabla_{\mathbf{x}} \|\mathbf{x} \|^2 = \nabla_{\mathbf{x}} \mathbf{x}^\top \mathbf{x} = 2\mathbf{x}.\\" />

* Similarly, for any matrix <img src="https://latex.codecogs.com/svg.image?\mathbf{X}$,&space;we&space;have&space;$\nabla_{\mathbf{X}}&space;\|\mathbf{X}&space;\|_F^2&space;=&space;2\mathbf{X}" title="\mathbf{X}$, we have $\nabla_{\mathbf{X}} \|\mathbf{X} \|_F^2 = 2\mathbf{X}" />. As we will see later, gradients are useful for designing optimization algorithms in deep learning.



### Formula
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

>> <img src="https://latex.codecogs.com/svg.image?&space;\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{1}&0&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x}&1&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^2}&\mathrm{2x}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^n}&\mathrm{nx^{n-1}}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{2x}&\mathrm{2&space;*&space;1}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{(1&plus;x^2)}&\mathrm{0&plus;2x=2x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{(1-x^2)}&\mathrm{0-2x=-2x}&space;&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{e^x}&\mathrm{e^x*&space;1=e^x}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{e^{f(x)}}&\mathrm{e^{f(x)*}}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sin&space;x}&\mathrm{\cos&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\cos&space;x}&&space;\mathrm{-\sin&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\tan&space;x}&&space;\mathrm{\sec^2&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\tan^{-1}&space;x}&&space;\mathrm{\frac{1}{1&plus;x^2}}&space;&space;\\&space;\end{array}" title=" \begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{1}&0 \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x}&1 \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^2}&\mathrm{2x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^n}&\mathrm{nx^{n-1}} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{2x}&\mathrm{2 * 1} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1+x^2)}&\mathrm{0+2x=2x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1-x^2)}&\mathrm{0-2x=-2x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^x}&\mathrm{e^x* 1=e^x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^{f(x)}}&\mathrm{e^{f(x)*}}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin x}&\mathrm{\cos x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\cos x}& \mathrm{-\sin x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan x}& \mathrm{\sec^2 x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan^{-1} x}& \mathrm{\frac{1}{1+x^2}} \\ \end{array}" width=30%/> 
>
>> <img src="https://latex.codecogs.com/svg.image?\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\sin^{-1}&space;x}&&space;\mathrm{\frac{1}{\sqrt{1&plus;x^2}&space;}}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sin&space;f(x)}&\mathrm{\cos&space;f(x)*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cos&space;f(x)}&\mathrm{-\sin&space;f(x)*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\left&space;[&space;f(x)&space;\right&space;]^n}&&space;\mathrm{n\left&space;[&space;f(x)&space;\right&space;]^{n-1}&space;*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{&space;f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cos^{-1}}x&&space;-\frac{1}{\mathrm{\sqrt{1&plus;x^2}&space;}&space;}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\log}x&&space;\frac{1}{x}&space;&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\frac{1}{\mathrm{x}}&\mathrm{-\frac{1}{x^2}}\because&space;\left&space;(&space;\frac{1}{x}=x^{-1}\right&space;)\mathrm{&space;(-1*x^{-1-1})}&space;&space;\\&space;\end{array}" title="\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\sin^{-1} x}& \mathrm{\frac{1}{\sqrt{1+x^2} }} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin f(x)}&\mathrm{\cos f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos f(x)}&\mathrm{-\sin f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\left [ f(x) \right ]^n}& \mathrm{n\left [ f(x) \right ]^{n-1} *}\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{ f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos^{-1}}x& -\frac{1}{\mathrm{\sqrt{1+x^2} } } \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\log}x& \frac{1}{x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \frac{1}{\mathrm{x}}&\mathrm{-\frac{1}{x^2}}\because \left ( \frac{1}{x}=x^{-1}\right )\mathrm{ (-1*x^{-1-1})} \\ \end{array}" width=50%/> 
>
>> <img src="https://latex.codecogs.com/svg.image?\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cot&space;x}&\mathrm{-cosec^2&space;x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sec&space;x}&\mathrm{\sec&space;x&space;\tan&space;x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\csc&space;x}&\mathrm{-\csc&space;x&space;\cot&space;x}&space;&space;\\&space;\end{array}&space;" title="\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cot x}&\mathrm{-cosec^2 x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sec x}&\mathrm{\sec x \tan x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\csc x}&\mathrm{-\csc x \cot x} \\ \end{array} " width=25%/>

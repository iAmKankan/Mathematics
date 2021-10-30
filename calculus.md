## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [Differential calculus](#differential-calculus)

## What is Calculus
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* Calculus is the branch of mathematics that deals with continuous change.
* Calculus is also called infinitesimal calculus or “the calculus of infinitesimals”. 
* The meaning of classical calculus is the study of continuous change of functions.
* Most of these quantities are the functions of time such as velocity is equal to change in distance with respect to time. 
* The two major concepts of calculus are: 
   * Integrals 
   * Differentials
  
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
> *  Suppose that functions  f  and  g  are both differentiable and  C  is a constant, we have the 
> #### Constant multiple rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[Cf(x)]\&space;=\&space;C&space;\frac{d}{dx}&space;f(x)," title="\frac{d}{dx} [Cf(x)]\ =\ C \frac{d}{dx} f(x)," />
> #### Sum rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[f(x)&space;&plus;&space;g(x)]\&space;=\&space;\frac{d}{dx}&space;f(x)&space;&plus;&space;\frac{d}{dx}&space;g(x)," title="\frac{d}{dx} [f(x) + g(x)]\ =\ \frac{d}{dx} f(x) + \frac{d}{dx} g(x)," />
> #### Product rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;[f(x)g(x)]\&space;=\&space;f(x)&space;\frac{d}{dx}&space;[g(x)]\&space;&plus;\&space;g(x)&space;\frac{d}{dx}&space;[f(x)]," title="\frac{d}{dx} [f(x)g(x)]\ =\ f(x) \frac{d}{dx} [g(x)]\ +\ g(x) \frac{d}{dx} [f(x)]," />
> #### Quotient rule
> <img src="https://latex.codecogs.com/svg.image?\frac{d}{dx}&space;\left[\frac{f(x)}{g(x)}\right]\&space;=\&space;\frac{g(x)&space;\frac{d}{dx}&space;[f(x)]&space;-&space;f(x)&space;\frac{d}{dx}&space;[g(x)]}{[g(x)]^2}." title="\frac{d}{dx} \left[\frac{f(x)}{g(x)}\right]\ =\ \frac{g(x) \frac{d}{dx} [f(x)] - f(x) \frac{d}{dx} [g(x)]}{[g(x)]^2}." />
> 
### Differential Calculus 
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* Differential calculus deals with the rate of change of one quantity with respect to another.
* The sighn of differentiation is _**d/d**_
* It is always done in respect to a variable or a function.
* That function / variable is written along side of the denominator _**d**_.
* And the thing to be differentiate is written alongside of the numerastor _**d**_.
* Suppose variable x is there and a is the number to be differentiate <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}a&space;}{\mathrm{d}x&space;}" title="\frac{\mathrm{d}a }{\mathrm{d}x }" />.
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

![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

### Formulas
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

#### Power Rule
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Here we use the power rule in order to calculate the derivative and it’s pretty simple though.


>> <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^2}=\mathrm{2x}" title="\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^2}=\mathrm{2x}" />

>>   <img src="https://latex.codecogs.com/svg.image?\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^n}=\mathrm{nx^{n-1}}" title="\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^n}=\mathrm{nx^{n-1}}" />

* The considered function f(x) is equal to x to the fifth.
> <img src="https://latex.codecogs.com/svg.image?\begin{cases}&space;&&space;\text{&space;if&space;}&space;f(x)=x^n&space;\\&space;&&space;\text{&space;then&space;}&space;f'(x)=n.x^{n-1}&space;\end{cases}&space;" title="\begin{cases} & \text{ if } f(x)=x^n \\ & \text{ then } f'(x)=n.x^{n-1} \end{cases} " />

> <img src="https://latex.codecogs.com/svg.image?\begin{cases}&space;&&space;f(x)=x^5&space;\\&space;&&space;f'(x)=5x^{(5-1)}&space;\\&space;&&space;f'(x)=5x^{4}&space;\end{cases}&space;" title="\begin{cases} & f(x)=x^5 \\ & f'(x)=5x^{(5-1)} \\ & f'(x)=5x^{4} \end{cases} " />

### Formula
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

>> <img src="https://latex.codecogs.com/svg.image?&space;\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{1}&0&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x}&1&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^2}&\mathrm{2x}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{x^n}&\mathrm{nx^{n-1}}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{2x}&\mathrm{2&space;*&space;1}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{(1&plus;x^2)}&\mathrm{0&plus;2x=2x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathbf{(1-x^2)}&\mathrm{0-2x=-2x}&space;&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{e^x}&\mathrm{e^x*&space;1=e^x}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{e^{f(x)}}&\mathrm{e^{f(x)*}}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sin&space;x}&\mathrm{\cos&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\cos&space;x}&&space;\mathrm{-\sin&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\tan&space;x}&&space;\mathrm{\sec^2&space;x}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\tan^{-1}&space;x}&&space;\mathrm{\frac{1}{1&plus;x^2}}&space;&space;\\&space;\end{array}" title=" \begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{1}&0 \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x}&1 \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^2}&\mathrm{2x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathbf{x^n}&\mathrm{nx^{n-1}} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{2x}&\mathrm{2 * 1} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1+x^2)}&\mathrm{0+2x=2x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathbf{(1-x^2)}&\mathrm{0-2x=-2x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^x}&\mathrm{e^x* 1=e^x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{e^{f(x)}}&\mathrm{e^{f(x)*}}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin x}&\mathrm{\cos x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\cos x}& \mathrm{-\sin x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan x}& \mathrm{\sec^2 x} \\\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\tan^{-1} x}& \mathrm{\frac{1}{1+x^2}} \\ \end{array}" width=30%/> 
>
>> <img src="https://latex.codecogs.com/svg.image?\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{\sin^{-1}&space;x}&&space;\mathrm{\frac{1}{\sqrt{1&plus;x^2}&space;}}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sin&space;f(x)}&\mathrm{\cos&space;f(x)*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cos&space;f(x)}&\mathrm{-\sin&space;f(x)*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}\mathrm{f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\left&space;[&space;f(x)&space;\right&space;]^n}&&space;\mathrm{n\left&space;[&space;f(x)&space;\right&space;]^{n-1}&space;*}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{&space;f(x)}&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cos^{-1}}x&&space;-\frac{1}{\mathrm{\sqrt{1&plus;x^2}&space;}&space;}&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\log}x&&space;\frac{1}{x}&space;&space;&space;\\&space;\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\frac{1}{\mathrm{x}}&\mathrm{-\frac{1}{x^2}}\because&space;\left&space;(&space;\frac{1}{x}=x^{-1}\right&space;)\mathrm{&space;(-1*x^{-1-1})}&space;&space;\\&space;\end{array}" title="\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{\sin^{-1} x}& \mathrm{\frac{1}{\sqrt{1+x^2} }} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sin f(x)}&\mathrm{\cos f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos f(x)}&\mathrm{-\sin f(x)*}\frac{\mathrm{d} }{\mathrm{d} x}\mathrm{f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\left [ f(x) \right ]^n}& \mathrm{n\left [ f(x) \right ]^{n-1} *}\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{ f(x)} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cos^{-1}}x& -\frac{1}{\mathrm{\sqrt{1+x^2} } } \\ \frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\log}x& \frac{1}{x} \\ \frac{\mathrm{d} }{\mathrm{d} x} \frac{1}{\mathrm{x}}&\mathrm{-\frac{1}{x^2}}\because \left ( \frac{1}{x}=x^{-1}\right )\mathrm{ (-1*x^{-1-1})} \\ \end{array}" width=50%/> 
>
>> <img src="https://latex.codecogs.com/svg.image?\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\cot&space;x}&\mathrm{-cosec^2&space;x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\sec&space;x}&\mathrm{\sec&space;x&space;\tan&space;x}&space;&space;&space;\\\frac{\mathrm{d}&space;}{\mathrm{d}&space;x}&space;\mathrm{\csc&space;x}&\mathrm{-\csc&space;x&space;\cot&space;x}&space;&space;\\&space;\end{array}&space;" title="\begin{array}{l@{\:=\:}*{1}{l@{}}l}\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\cot x}&\mathrm{-cosec^2 x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\sec x}&\mathrm{\sec x \tan x} \\\frac{\mathrm{d} }{\mathrm{d} x} \mathrm{\csc x}&\mathrm{-\csc x \cot x} \\ \end{array} " width=25%/>

## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* [Differential calculus](#differential-calculus)


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

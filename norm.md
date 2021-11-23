## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## Norms
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* Used for measuring the size of a vector
* Norms map vectors to non-negative values
* Norm of vector <img src="http://latex.codecogs.com/svg.image?x=[x_1,x_2,..,x_n]^\top" title="x=[x_1,x_2,..,x_n]^\top" /> is distance from origin to x.

## <img src="http://latex.codecogs.com/svg.image?L^P&space;" title="L^P " width=4%/> Norm
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)

> ### <img src="http://latex.codecogs.com/svg.image?L^2&space;" title="L^2 " width=3%/> Norm
* Called Euclidean norm - Simply the Euclidean distance between the origin and the point a






## What is norm
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)
* In mathematics, a norm is a **function** from a real or complex vector space to the nonnegative real numbers that behaves in certain ways like the distance from the origin: 
* It commutes with scaling, 
   * obeys a form of the triangle inequality.
   * is zero only at the origin.
* In particular, the Euclidean distance of a vector from the origin is a norm, called the Euclidean norm, or 2-norm, which may also be defined as the square root of the inner product of a vector with itself.

> #### Norm, is a quantity that describs the size of a vector(mathematical vector).

> * Suppose we have two vectors
>>  <img src="https://latex.codecogs.com/svg.image?\\&space;\vec{a}=&space;\begin{Bmatrix}&space;4\\3\end{Bmatrix}&space;\mathrm{\&space;and&space;\&space;}\vec{b}=&space;\begin{Bmatrix}&space;-1\\1\end{Bmatrix}&space;" title="\\ \vec{a}= \begin{Bmatrix} 4\\3\end{Bmatrix} \mathrm{\ and \ }\vec{b}= \begin{Bmatrix} -1\\1\end{Bmatrix} " />

> ### The problem is how to measure the distance between these two vectors?

> #### Solution 1: Inorder to find out the distance between those two vectors at first we need to measure the distances of those two points from the origin.
> * The distance from the origin to vector a is 5 and origin to vector b is <img src="https://latex.codecogs.com/svg.image?\sqrt{2}" title="\sqrt{2}" />

> ### L2 Norm:
>> <img src="https://latex.codecogs.com/svg.image?\l_2\&space;norm&space;\&space;/&space;Eucladean\&space;Distance\&space;=&space;\left&space;(&space;\sum_{i=1}^{k}|X_{i}|^{2}&space;\right&space;)^{\frac{1}{2}}&space;" title="\l_2\ norm \ / Eucladean\ Distance\ = \left ( \sum_{i=1}^{k}|X_{i}|^{2} \right )^{\frac{1}{2}} " />

<img src="https://user-images.githubusercontent.com/12748752/141727741-6d7f2d7b-5ee2-4a0b-8fe1-d004be7b65ee.png" width=50%/>

> ### L1 Norm:
>> <img src="https://latex.codecogs.com/svg.image?\l_1\&space;norm&space;\&space;/&space;Manhattan&space;\&space;Norm\&space;=&space;\left&space;(&space;\sum_{i=1}^{k}|X_{i}|^{1}&space;\right&space;)^{\frac{1}{1}}" title="\l_1\ norm \ / Manhattan \ Norm\ = \left ( \sum_{i=1}^{k}|X_{i}|^{1} \right )^{\frac{1}{1}}" />
<img src="https://user-images.githubusercontent.com/12748752/141729610-5eaf179c-a9b3-43c1-9ba6-b06cb528e566.png" width=50%/>

> ### Generalizing Norm:
> * l_n norm is the nth root of the summetion of all components to their powers. 
>> <img src="https://latex.codecogs.com/svg.image?\l_n\&space;norm&space;\&space;/&space;Generalized\&space;Norm\&space;=&space;\left&space;(&space;\sum_{i=1}^{k}|X_{i}|^{n}&space;\right&space;)^{\frac{1}{n}}" title="\l_n\ norm \ / Generalized\ Norm\ = \left ( \sum_{i=1}^{k}|X_{i}|^{n} \right )^{\frac{1}{n}}" />

### Usesage of Norm
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

> ### Mean Squared Error 

>> <img src="https://latex.codecogs.com/svg.image?\frac{1}{m}&space;\sum_{i=1}^{m}(Y_i-\hat{Y_i})^2" title="\frac{1}{m} \sum_{i=1}^{m}(Y_i-\hat{Y_i})^2" />
>
> * Can be written as-
>> <img src="https://latex.codecogs.com/svg.image?\frac{1}{m}&space;[\l_2\&space;norm(Y_i-\hat{Y_i})]^2" title="\frac{1}{m} [\l_2\ norm(Y_i-\hat{Y_i})]^2" />


---

> ### Regularization where we put Constraint on weights

> #### Ridge Regression Constraint
>> <img src="https://latex.codecogs.com/svg.image?\sum_{i=1}^{k}w_i^2&space;\&space;\leq\&space;\sqrt{r}" title="\sum_{i=1}^{k}w_i^2 \ \leq\ \sqrt{r}" />
> * Can be written as
>> <img src="https://latex.codecogs.com/svg.image?\l_2&space;\&space;norm&space;(w)&space;\&space;\leq\&space;\sqrt{r}" title="\l_2 \ norm (w) \ \leq\ \sqrt{r}" />


> #### Lasso Regression
>> <img src="https://latex.codecogs.com/svg.image?\sum_{i=1}^{k}|w_i|\&space;\leq\&space;r" title="\sum_{i=1}^{k}|w_i|\ \leq\ r" />
> * Can be written as
>> <img src="https://latex.codecogs.com/svg.image?\l_1&space;\&space;norm(w)\&space;\leq\&space;r" title="\l_1 \ norm(w)\ \leq\ r" />

## References
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

* [YouTube](https://www.youtube.com/watch?v=FiSy6zWDfiA)
* [Video](https://www.youtube.com/watch?v=aMLl6jUlpqA)
* "ML Algebra" by Srihari

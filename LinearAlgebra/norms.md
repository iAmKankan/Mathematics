## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)


## Norms in ML
The basic reason why machine learning and many other fields use norms is because we usually use **vectors** or **matrices** as our **basic units of representation**. In fact anything that goes our input or output is usually measured by **vectors** and **matrices**. Norm is the _generalization_ of the notion of **_length_** to **vectors**, **matrices** and **tensors**

#### There are two basic reasons that we use norms in Machine Learning-
1) **_To find out the size of a vector or a tensor_**
2) **_To estimate the proximity of two vector/tensor_**


<b>1. <ins><i>To find out how big or small a particular vector or tensor is (Size/length)</i></ins></b>**:** Sometimes we need to estimate the size of an object- **i.g.** for a **scalar** a _weight_ or _pressure_ or _temperature_ there is **one single number** by which we can get the idea of how big this thing is, whether it is negative or positive the absolute value usually denotes what the size is for a scalar. For a **vector** we have no such single number coz it is a bunch of numbers. 

<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{Norms&space;is&space;to&space;map&space;from&space;a&space;\underline{Vector}&space;or&space;\underline{Tensor}&space;to&space;a&space;\underline{Scaler}(&plus;ve)&space;value}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{Norms is to map from a \underline{Vector} or \underline{Tensor} to a \underline{Scaler}(+ve) value}}" align="center" />
 
 #### Example #1
<img src="https://user-images.githubusercontent.com/12748752/184543636-a6340663-4c85-4fbc-b85b-4c0767702553.png" width=20%/>

<b>2. <ins><i>To estimate how close one tensor is to another(Proximity)</i></ins></b>**:** 
   * That is how "big" the difference between two tensors is 
   * **Example**: How close is one image to another?


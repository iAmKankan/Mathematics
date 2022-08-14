## Index
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)


## Norms in ML
**_A simple vector that we are trying to findout its length._**

The basic reason why machine learning and many other fields use norms is because we usually use **vectors** or **matrices** as our **basic units of representation**. In fact anything that goes our input or output is usually measured by **vectors** and **matrices**. Norm is the _generalization_ of the notion of **_length_** to **vectors**, **matrices** and **tensors**

#### There are two basic reasons that we use norms in Machine Learning-
1) **_To find out the size of a vector or a tensor_**
2) **_To estimate the proximity of two vector/tensor_**


<b>1. <ins><i>To find out how big or small a particular vector or tensor is (Size/length)</i></ins></b>**:** Sometimes we need to estimate the size of an object- **i.g.** for a **scalar** a _weight_ or _pressure_ or _temperature_ there is **one single number** by which we can get the idea of how big this thing is, whether it is negative or positive the absolute value usually denotes what the size is for a scalar. For a **vector** we have no such single number coz it is a bunch of numbers. 

<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{Norms&space;is&space;to&space;map&space;from&space;a&space;\underline{Vector}&space;or&space;\underline{Tensor}&space;to&space;a&space;\underline{Scaler}(&plus;ve)&space;value}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\textbf{Norms is to map from a \underline{Vector} or \underline{Tensor} to a \underline{Scaler}(+ve) value}}" align="center" />
 
* The usual notion of length of a norm is denoted by **parallel** or **double bar** or  **||x||** sign, just like for scalar we use **|&alpha;|** for absolute values.

 #### Example #1
<img src="https://user-images.githubusercontent.com/12748752/184551530-c001d8d0-da77-49a9-b829-ae2bb145e9e5.png" width=20%/>

The length of the vector **v=[3, 4]** is **5**

<b>2. <ins><i>To estimate how close one tensor is to another(Proximity)</i></ins></b>**:** 
   * That is how "big" the difference between two tensors is 
   * i.e. How close is one image to another?
#### Example #1
<img src="https://user-images.githubusercontent.com/12748752/184551915-eee5194c-45bb-4443-b0ae-6aa95db7d8ac.png" width=20%/>

* So, the difference between two vector is another vector(as we already know) here 

  <img src="https://latex.codecogs.com/svg.image?\\{\color{Purple}\Delta&space;\textbf{v}=&space;\textbf{v}_1-\textbf{v}_2&space;}\\{\color{Purple}\parallel\Delta&space;\textbf{v}\parallel=&space;\parallel\textbf{v}_1-\textbf{v}_2&space;\parallel}&space;" title="https://latex.codecogs.com/svg.image?\\{\color{Purple}\Delta \textbf{v}= \textbf{v}_1-\textbf{v}_2 }\\{\color{Purple}\parallel\Delta \textbf{v}\parallel= \parallel\textbf{v}_1-\textbf{v}_2 \parallel} " />

### Definition of Norms
Norms is a way of measuring the length of a Vector or Metrices etc

Mathemetically norms is any function _f_ that satisfies
1. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}f(\textbf{x})=0&space;\Rightarrow&space;\textbf{x}=0}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple}f(\textbf{x})=0 \Rightarrow \textbf{x}=0} " align="center"/> - If the vector is **0** (**x=0**) then its length (or norm) is **0** [ At the origin of the **x,y** coordinate].
2. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}f\mathbf{(v_1&plus;v_2)}\leq&space;f\mathbf{(v_1)}&plus;f\mathbf{(v_2)}&space;\textrm{,&space;(Triangle&space;Inequality)}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple}f\mathbf{(v_1+v_2)}\leq f\mathbf{(v_1)}+f\mathbf{(v_2)} \textrm{, (Triangle Inequality)}} " align="center"/>. Now what the **triangle inequality rule** for the **norm** says is that the length of _f_(x + y) has to be always less that the length of _f_(x) plus the length of _f_(y) , we know this from the **normal triangle inequality**, the length of two sides is always going to be larger than the length of the third side, **the sum of two sides** is always going to be **larger than the third side** that is because the shortest distance between any two points is a straight line.
<img src="https://user-images.githubusercontent.com/12748752/184553296-168a93e1-ebb9-487a-8caa-37a551ca7088.png" width=20%/>

3. <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\forall&space;\alpha&space;\in&space;\mathbb{R},}\&space;\&space;f\mathbf{(\alpha&space;v)}=|\alpha|&space;f\mathbf{(v)}&space;\textrm{,&space;(Linearity)}}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\forall \alpha \in \mathbb{R},}\ \ f\mathbf{(\alpha v)}=|\alpha| f\mathbf{(v)} \textrm{, (Linearity)}}" align="center" />. If we increase the length of the vector, suppose increase both coordinate by the factor of e.g **2** (here **&alpha;**) then its norms should be increase by the factor of **2** (here **&alpha;**)
<img src="https://user-images.githubusercontent.com/12748752/184554702-8449c6cf-ce3a-4765-bd3c-fd5d088cc0b7.png" width=25%/>

#### From above three rules we can derive other formulas like- 
* <img src="https://latex.codecogs.com/svg.image?{\color{Purple}f(\overrightarrow{\mathbf{v}})&space;\mathbf{\rightarrow&space;Scaler(&plus;ve)}" title="https://latex.codecogs.com/svg.image?{\color{Purple}f(\overrightarrow{\mathbf{v}}) \mathbf{\rightarrow Scaler(+ve)}" align="center"/>
 
 ### Vector Norms
**Suppose we have a vector**  
 <img src="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}}&space;=&space;\begin{bmatrix}\mathbf{-5}&space;\\\mathbf{3}\\\mathbf{2}\\\end{bmatrix}}&space;" title="https://latex.codecogs.com/svg.image?{\color{Purple}\overrightarrow{\mathbf{v}} = \begin{bmatrix}\mathbf{-5} \\\mathbf{3}\\\mathbf{2}\\\end{bmatrix}} " align="center"/>, severel norms can be used on this simple vector such as the following-
 
### 1. **_Euclidean Norm_** or **_Pythagorean Norm_** or **_2- Norm_** or **_L_<sup>2</sup>** 
<img src="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\parallel&space;v&space;\parallel_2}&space;=&space;(\mathbf{v_1^2}&space;&plus;&space;\mathbf{v_2^2}&space;&plus;&space;\mathbf{v_2^2}&space;&plus;&space;\cdots&space;&plus;\mathbf{v_n^2}&space;)^{\mathbf{\frac{1}{2}}&space;}&space;}" title="https://latex.codecogs.com/svg.image?{\color{Purple}\mathbf{\parallel v \parallel_2} = (\mathbf{v_1^2} + \mathbf{v_2^2} + \mathbf{v_2^2} + \cdots +\mathbf{v_n^2} )^{\mathbf{\frac{1}{2}} } }" align="center"/> 

  * The result would be <img src="https://latex.codecogs.com/svg.image?{\color{Purple}&space;\parallel&space;\overrightarrow{\mathbf{v}}&space;\parallel&space;=&space;\sqrt{\mathbf{5^2&plus;3^2&plus;2^2}}&space;\\&space;\approx&space;6.16}" title="https://latex.codecogs.com/svg.image?{\color{Purple} \parallel \overrightarrow{\mathbf{v}} \parallel = \sqrt{\mathbf{5^2+3^2+2^2}} \\ \approx 6.16}" align="center"/>


 
 
 

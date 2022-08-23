## Index
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

## Vector Space Models for NLP
![dark](https://user-images.githubusercontent.com/12748752/132402918-976c6cc7-cc94-4267-9513-b3937504eb63.png)

### 2-D Vector Space
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A **2-D** vector-space Is defined as a set of linearly independent basis vectors with 2 axes. Each axis corresponds to a dimension in the vector-space. 

<img src="https://user-images.githubusercontent.com/12748752/186020910-9eeae053-e951-434a-9f3e-ac812fbbf05a.png" width=50%/>

### 3-D Vector Space
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
A **3-D** vector-space is defined as a set of linearly Independent basis vectors with 3 axes. Each axis corresponds to a dimension in the vector-space.

<img src="https://user-images.githubusercontent.com/12748752/186029942-00189cf6-bb7a-4f0d-97fe-04d71b1d203f.png" width=50%/>

Linearly independent vectors of size **N** will result in **N**-dimensional axes which are mutually orthogonal to each other. 

### Vector Space model for Words
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
Let us assume that the words in a corpus are considered as linearly independent basis vectors. If a corpus contains 1 words which are linearly independent, then every word represents an axis in the continuous vector space R. Each word takes an independent axis which is orthogonal to other words/axes. Then will contain | axes.

#### Examples
1. The vocabulary size of emma corpus is 7079) If we plot all the words in the real space R, we get 7079 axes
2. The vocabulary size of Google News Corpus corpus is 3 million. If we plot all the words in the real space R, we get 3 million axes

Suppose if you are having about 300 words, all 300 words are **independent** and they have no relation to each other(considered as **_linearly independent vectors_**); that means if I do a dot product of word **a** and **b** that result would be going to be **0**. So, again we will be using the notation of **|v|** this length of your vocabulary if you consider all of them as linear and then all the vectors related to the words in the vocabulary or linearly independent. And they do not have a linear relationship with each other and they are represented in the
continuous vector spacer. 

### DOCUMENT VECTOR SPACE MODEL
![light](https://user-images.githubusercontent.com/12748752/132402912-1a2a215e-de2f-4536-b28e-e75197136af9.png)
* Vector space models are used to represent words in a continuous vector space **R**.
* Combination of Terms represent a document vector in the word vector space.
* Very high dimensional space - several million axes, representing terms and several million documents containing several terms

#### EXAMPLE BINARY INCIDENCE MATRIX
Let us consider three words - **good**, **car**, **mechanic** and we will represent these words in a 3-D vector space

<img src="https://user-images.githubusercontent.com/12748752/186108579-79c183ea-d8fd-403d-b370-05a2244e5ab8.png" width=20% align="right"/>

| |good|car|mechanic|
|----|----|---|----|
|D1|1|1|1|
|D2|1|0|1|
|D3|0|1|1|


#### TF-IDF represent these words like
| |good|car|mechanic|
|----|----|---|----|
|D1|0.91|1|0.0011|
|D2|0.21|0|0.1|
|D3|0.15|1|0.921|

<img src="https://user-images.githubusercontent.com/12748752/186113858-3b37fed8-8935-4941-9635-cc0496af8ed7.png" width=20% align="right"

## Index
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)

## Why we need Probability in NLP?
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)
*  Provides methods to predict or make decisions to pick the next word in the sequence based on sampled data
*  Make the informed decision when there a certain degree of uncertainty and some observed data
*  It provides a quantitative description of the chances or likelihoods associated with various outcomes
*  Probability of a sentence
*  Probability of the next word in a sentence - how likely to predict "you" as the next word
*  Likelihood of the next word is formalized through an observation by conducting experiment - counting the words in a document
Discrete Sample Space, experiment, joint and conditional probability,

### Probabilistic Language Model
![light](https://user-images.githubusercontent.com/12748752/126882430-cb0aa865-0c15-43f9-85d6-e6ce589c8772.png)

**Goal:** Compute the probability of a sequence of words

$$\large{\color{Purple} 
\begin{equation}
P(W) P(w_1, w_2, w_3,\cdots ,w_n) \small{\color{Black}\ \ \ \ \ \ \ \ \ \ \ \ \ \ \textbf{(1)}}
\end{equation}
}
$$

**Task:** To predict the next word using probability. Given the context, find the next word using

$$\large{\color{Purple} 
\begin{equation}
 P(w_n|w_1, w_2, w_3,\cdots ,w_{n-1})  \small{\color{Black}\ \ \ \ \ \ \ \ \ \ \ \ \ \ \textbf{(2)}}
\end{equation}
}
$$


A model which computes the probability for **(1)** or predicting the next word **(2)** or complete the partial sentence is called as Probabilistic Language Model. The goal is to learn the joint probability function of sequences of words in a language. The probability of **_P(The cat roars)_** is less likely to happen than **_P(The cat meows)_** **n-grams** are used to build predictive and generative language models

### Vector space
![light](https://user-images.githubusercontent.com/12748752/126882430-cb0aa865-0c15-43f9-85d6-e6ce589c8772.png)
* Let us assume that the words in a corpus are considered as linearly independent basis vectors.
* If a corpus contains $\large{\color{Purple}\mathbb{|\mathbb{N}|}}$ words which are _linearly independent_, then every word represents an axis in the continuous vector space $\large{\color{Purple}\mathbb{R}}$.
* Each word takes an independent axis which is [orthogonal](https://en.wikipedia.org/wiki/Orthonormality)(perpendicular) to other words/axes. 
* Then $\large{\color{Purple}\mathbb{R}}$ will contain $\large{\color{Purple}\mathbb{|\mathbb{N}|}}$ axes.

#### Examples
1. The vocabulary size of emma corpus is 7079. If we plot all the words in the real space $\large{\color{Purple}\mathbb{R}}$, we get 7079 axes
2. The vocabulary size of Google News Corpus corpus is 3 million. If we plot all the words in the real space $\large{\color{Purple}\mathbb{R}}$ , we get 3 million axes

### CREATION OF SEMANTICALLY CONNECTED VECTORS
* Identify a model that enumerates the relationships between terms and documents
* Identify a model that tries to put similar items closer to each other in some space or structure
* A model that discovers/uncovers the semantic similarity between words and documents in the latent semantic domain
* Develop a distributed word vectors or dense vectors that captures the linear combination of word vectors in the transformed domain
### WHY DENSE VECTORS?
* Sparse vectors are too long and not very convenient as features machine learning
* Abstracts more than just frequency counts
* It captures neighborhood words that are connected by synonyms
  * Consider these two documents (1) Automobile association (2) car driver
  * Connects the neighbor of Automobile and the neighbor of car 
  * "Automobile association" with "car driver" - driver and association could be connected using the similar words _Automobile_ and _car_

### HUMAN/MACHINE LEARNING
* How do we solve problems when we lack sufficient knowledge?
* Finding Examples and using experience gained are useful
* Examples provide certain underlying patterns
* Patterns give the ability to predict some outcome or help in constructing an approximate model
* The model may help resolve some problems, though may not be an ideal one
* Learning is the key to the ambiguous world * Linear and non-linear classification
* Perceptron, perceptron learning, cost function, feed forward neural network, back propagation algorithm



## Reference
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)
* [Applied Natural Language Processing Prof. Ramaseshan Ramachandran Department of Computer Science and Engineering Chennai Mathematical Institute, Madras](https://archive.nptel.ac.in/courses/106/106/106106211/)

## Index
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)
![light](https://user-images.githubusercontent.com/12748752/126882430-cb0aa865-0c15-43f9-85d6-e6ce589c8772.png)

## Why we need Probability in NLP?
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)
*  Provides methods to predict or make decisions to pick the next word in the sequence based on sampled data
*  Make the informed decision when there a certain degree of uncertainty and some observed data
*  It provides a quantitative description of the chances or likelihoods associated with various outcomes
*  Probability of a sentence
*  Probability of the next word in a sentence - how likely to predict "you" as the next word
*  Likelihood of the next word is formalized through an observation by conducting experiment - counting the words in a document
Discrete Sample Space, experiment, joint and conditional probability,

### PROBABILISTIC LANGUAGE MODEL
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


A model which computes the probability for **(1)** or predicting the next word **(2)** or complete the partial sentence is called as Probabilistic Language Model. The goal is to learn the joint probability function of sequences of words in a language. The probability of P(The cat roars) is less likely to happen than P(The cat meows) n-grams are used to build predictive and generative language models

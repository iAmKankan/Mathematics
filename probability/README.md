## Index
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)



## Probability
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)
The word **probability** literally denotes ‘_chance_’, and the **theory of probability** deals  with **laws governing the chances of occurrence of phenomena** which are **unpredictable**  in nature.  

**Probability** is a **mathematical framework** for **representing uncertainty** wherever you have some uncertain outcome, we tend to use probability as a mathematical representation of the uncertainty in the problem. 

**Probability** in **machine learning** there are two primary uses of that, 
   1) **_Constructing learning systems_** is nothing but _Machine Learning models_. 
      * **Example:** If you try and mimic let's say_ human reasoning about uncertainty_ we say the _probability of rain is probably sixty percent tomorrow_. inherently even within our models there is some probability built in. 
      * In order to incorporate such probabilistic thinking you have **probabilistic models**.
      
   2) **_Analysing Learning Systems_** a _deterministic model_ 
       * Many neural network models are almost by design they are deterministic so you could have a deterministic Model.
       * That is how the **input relates to the output** is actually a deterministic process. Nonetheless the output itself can be analyzed probabilistically because the learning system is only correct part of the time. It's not correct all the time.
       * **Example** if you might see a Google Image analyzer or any other image analyzer. Typically, the actual output in the algorithm will not be a specific class. 75% of dog

### Frequentist vs Bayesian
![light](https://user-images.githubusercontent.com/12748752/126882430-cb0aa865-0c15-43f9-85d6-e6ce589c8772.png)
**Probability** lies between **0** and **1**. In probabilistic analysis there are two interpretations of what a particular probability means.

**Example:** Statement-  _There is 60% chance of rain tomorrow_. This can be interpreted in two distinct ways. 
  1) **Frequentist**: Frequentist model would be like - _the temperature rise this much the pressure today so much it's slightly cloudy and in all such cases before then such things happen in sixty percent of the times it rained_. 
       *  So such a statement would depend on something like what you have observed so far. And that's a frequentist approach to probability. 
       *  It says it depends on the **proportion** of events in an infinite sample space. 
       *  **An objective measure** - if I throw a dice let's say **millions** of times **two** will come up about one **sixth of the times**. So the probability is **one sixth**, This is an object to measure.
  2) **Bayesian**: Preferred typically by economists or even philosophers this actually measures degree of belief.
       * **Measures degree of belief** like- So it looks kind of likely that I am going to get about rain a little bit more than I but I am not really sure. So something of that sort it's a rough estimate.
       * **Subjective  measure**

#### Mathematics of resulting probabilities works the same way, at the end of the day it is the same mathamatics- 
**P(Disease 1)** = **0.1, P(Disease 2)** = **0.2, P(D 1&D 2)** = **0.02, if they are independent**

## Definitions
![deep](https://user-images.githubusercontent.com/12748752/126882429-37cbd66d-213c-4c00-b145-37773c820bf3.png)

#### ■ Random experiment - 
Experiment that results in different outcomes despite being seemingly similar conditions.

**Example** - **Tossing of a coin**, **throwing of a dice**, **rainfall amount**.
  * I toss a coin, it seems to me that I am keeping the coin exactly the same way on my thumb, and I get heads and sometimes get tails, such an experiment is called a random experiment. 
  * So rainfall amounts, throwing off dice are infinite examples of this.

#### ■ Sample space 
_Set of all possible outcomes of a random - experiment_.

 * **Example:** Tossing of a coin. 

$$\large{\color{Purple} 
\begin{align*}
& \textbf{ S=\\{H ,T \\} } & {\color{Black} \textit{ Tossing of a coin once} }\\ 
& \textbf{ S=\\{HH ,H T ,TH ,TT \\} } & {\color{Black} \textit{ Tossing of a coin twice} }\\ 
\end{align*}
}
$$

* The sample space we choose depends on the purpose of analysis
* **Example:** Diameter of a manufactured pipe. S could be -

$$\large{\color{Purple} 
\begin{align*}
& S=\mathbb{R}^+ = \\{x|x>0 \\} \ \ \ \ OR & {\color{Black} \textit{ [The positive half of the real number line]} }\\ 
& S=\\{low, medium, high\\} \ \ \ \ OR & {\color{Black} \textit{ [The diameter of the pipe low,mid,high]} }\\ 
& S=\\{satisfactory, unsatisfactory\\} & {\color{Black} \textit{ [The product is either or]} }\\ 
\end{align*}
}
$$ 

#### ■ Random Variable
The variable that associates a number with an outcome of **random experiment** is called a **random variable**. Random variable by itself is something that is mapped, to either the **Real number &reals;** or the **Integers** **&integers;**
* Can be done even for categorical outcomes
* The variable that associates a number with an outcome of a random experiment is called a random variable → **&reals;**,**&integers;**

**Notation** - The random variable is denoted by a capital letter (e.g **X**) and its value is denoted by a small letter (e.g. x). 
* **Example:** The rainfall on a particular day is a random variable..
     * We can ask "What is the probability that the rainfall is greater than 10mm?" 
<p align="center">
   <img src="https://latex.codecogs.com/svg.image?\large{\color{Purple}&space;\begin{align*}&&space;\textrm{&space;What&space;is&space;the&space;}&space;\underbrace{\mathrm{probability}}_{\mathbf{P}}&space;\textrm{&space;of&space;the&space;}&space;\underbrace{\mathrm{rainfall}}_{\mathbb{R}}&space;\textrm{&space;is&space;greater&space;than&space;}&space;\underbrace{10}_{\mathbf{r}}&space;\textrm{&space;mm?}&space;\\\end{align*}}" title="https://latex.codecogs.com/svg.image?\large{\color{Purple} \begin{align*}& \textrm{ What is the } \underbrace{\mathrm{probability}}_{\mathbf{P}} \textrm{ of the } \underbrace{\mathrm{rainfall}}_{\mathbb{R}} \textrm{ is greater than } \underbrace{10}_{\mathbf{r}} \textrm{ mm?} \\\end{align*}}" />
</p>


$$
\large{\color{Purple} 
\begin{align*}
& \textrm{By the mathametical notation P(R>10) = ?}
\end{align*}
}
$$ 
 
#### ■ Probability Distributions
A **probability distribution** tells us how likely a random variable is to take each of its possible states. A random variable can pick any state depending on what the sample space is. If the sample space has 10 members. Then the random variable can take any of the 10 values any of the 10 values not all 10 values simultaneously. Any of the 10 values.

The probability distribution tells us that not all of them might be equally likely. Some of them might be less likely. Some of them might be more likely. So that probability distribution is what tells you how likely each one of these values is.
  
  *  ■ **Discrete Random Variable (RV)**
     * Has finite (or countably infinite) range
     * **Example** - No. of typographical errors, no. of diagnostic errors, etc
     * Probability measured by **Probability Mass Function (PMF)**
     
  * ■ **Continuous Random Variable (RV)**
     * Has real number interval for its range.
     * **Example** - Temperature, Pressure, Voltage, Height, Current, etc
     * Probability measured by **Probability Density Function (PDF)**
 
  * ■ **Probability Mass Function (PMF)** _Discrete Variable -> Probability Mass Function (PMF)_
      * List of possible values along with their probabilities. 
      * **Example:**  So let's say you have a bias dice a bias dice means not all six sides are equally likely. So one is somewhat likely two has a different probability etc. So let's say we have these six probabilities.

$$
\large{\color{Purple} 
\begin{align*}
& \normalsize\textrm{X: number that comes up on throw of a bised die.}\\
& \textbf{P(X=1)=0.1 , }  \textbf{ P(X=2)=0.1 , }  \textbf{ P(X=3)=0.2 }\\
& \textbf{P(X=4)=0.2 , }  \textbf{ P(X=5)=0.2 , }  \textbf{ P(X=6)=0.2 }\\
\end{align*}
}
$$ 
     
 * To be a **PMF** for a random variable X, a function P satisfies: 
    * Domain of P is the set of all possible states of X 
    * $\large{\color{Purple}0 ≤ P(X = x) ≤ 1}$
    * $\large{\color{Purple} \sum_{x \in X} P(X = x) = 1}$

 * Uniform random variable: $\large{\color{Purple} P(x = x_i)=\frac{1}{k}}$
 * Analogous to a **point load**

<p align="center">
   <img src="https://user-images.githubusercontent.com/12748752/190042871-cb162953-f98a-4969-8fad-d011ad4c1981.png" width=40% />
   <br> <ins><b><i>PMF, Point load </i></b></ins>
</p>
     
   * ■ **Continuous Variable** -> **Probability Density Function (PDF)**
      * **PDF - Probability density**. In **1D**, **p(x)** is probability **"per unit length"**
      * What it is effectively is a probability per unit length, once again you can make an analogy so instead of a point Load. You now have something like a distributed load since this is a continuous function. We don't have gaps between any two random variables. 

<p align="center">
   <img src="https://user-images.githubusercontent.com/12748752/190046964-96620743-3084-4a64-921d-6fef492f2f2c.png" width=20% align="center"/>
    <br> <ins><b><i>Distribution</i></b></ins>
</p>

 [**To be continued**]
 
![light](https://user-images.githubusercontent.com/12748752/126882430-cb0aa865-0c15-43f9-85d6-e6ce589c8772.png)
 
 
Above discurssion was when we have single variable. Now the following are simple ideas when you have more than one variable. Now we are going to look at more than one random variable.
 <p align="center">
   <img src="https://user-images.githubusercontent.com/12748752/190052588-88be646c-ca04-4955-8dd1-5a58908bb42d.png" width=40% />
   <br> <ins><b><i>Left: Red bucket, 6 Oranges and 2 Apples |  Right: Blue bucket, 3 Apples and 1 Oranges</i></b></ins>
</p>

So imagine that you have two baskets. 
   * One of these is a **red basket** and one of them is a **blue basket** and each of these baskets has some fruits. 
   * The orange ones you can assume are **oranges** and the green ones we will assume are **apples**. 
Our task is to _randomly put our hand into one of the baskets and pick out a fruit_. Assume that all of them are well mixed and so if you are going to put your hand in one of the baskets, you will randomly pick out one of these fruits with equal probability. 
   * So this **red basket** therefore has **six oranges** and **two apples**. This **Blue basket** here has **three apples** and **one orange**. 
   * Further assume that your **choice of one basket** or the other is **not equally probable but that picking up**. So, Let us say-
        * The **red basket** you pick up with the probability of **0.4**,(**40%**)  $\large P(B=r)=0.4$ . 
        * And **60%** of the times you will pick the **blue basket**, $\large P(B=b)=0.6$ .

The **Random variables** we have here are 
   1) **B:** which **basket** we pick.
   2) **F:** which **fruit** we pick.
 
 $$
\large{\color{Purple} 
\begin{align*}
\textrm{Random variables}&\\
& B &: \\{b, r\\}\\
& F &: \\{o, a\\}\\
\end{align*}
}
$$ 
 
#### Questions
1) What is the probability of picking an orange?
2) What is the probability that I picked the red basket given that the fruit I picked was an orange?

#### Let us take a case where I take N = 100 trials.
<p align="center">
   <img src="https://user-images.githubusercontent.com/12748752/190077077-1fd3ebf4-5f19-40bf-9765-86d714798c2f.png" width=80% />
   <br> <ins><b><i></i></b></ins>
</p>


So, I have **100 trials** the basket will be **red** for total of **40 times**. Similarly the basket will be **blue** a total of **60 times**.
1) Now the **40 times** that I pick **red basket**, suppose I want to know - _how many of the cases will the fruit be an orange_? 
    * According to the probability **sixth-eight** of the cases which is **30** of the cases you are going to get an **orange**. 
    * **Two-eight** of the cases, ten of the cases you get an **apple**. 
So a **red basket** with an apple occurs **ten times**. 
2) Now , **60 times** of the cases are the **blue basket**, 
     * An **orange** comes **one-fourth** of **60** which turns out to be **15**. 
     * And we know now that the rest of the **45** cases we must actually be picking an **apple**. 

**100 trials what does it mean?** In each trial you pick the **basket** and chose a **fruit**. So amongst those **45** of the times we actually picked an **orange** and **55** times we actually picked an **apple**.

So you can see **basket is red**, **basket is blue** and I have written this table out which tells which, how many of these cases, remember each of these cases actually indicate an intersection of the **two cases**, **basically both these cases occur together**.

### Joint Probability (Discrete)
<p align="center">
   <img src="https://user-images.githubusercontent.com/12748752/190089983-ce87e4aa-4d1f-48ba-bd1d-77d234b135f2.png" width=40% />
   <br> <ins><b><i></i></b></ins>
</p>



$$
\large{\color{Purple} 
\begin{align*}
Generalize&\\
& X : x_i ,i=1 ,\cdots ,m\\
& Y : y_j , i=1,\cdots ,n\\
\end{align*}
}
$$ 

Now we can generalize this to two variables. Let us say you have a variable **X** and a variable **Y** just like in this case we had **B** and **F**, **basket** and **fruit**. 
* In this case we have chosen m=5 and n=3.

**_Joint probability_** is the probability that **X** will take desired value **x<sub>i</sub>** and **Y** will take some desired value **y<sub>j</sub>**. **For example**, in this case I could ask - 
#### ■ What is the probability that the *basket is red* and the *fruit is orange*? 
**Answer:** **P(B = r, F = o)** So that would be an example of a **joint probability**. 

So you write it under the notation, 
$$\Huge{\color{Purple}\boxed{P(X=x_i, Y=y_j)}}$$ 

In our case - **basket is red** and the ***fruit is orange*** 
$$\large{\color{Purple}P(B = r, F = o) = \frac{30}{100} =0.3}$$

Let the number of trials that $\large{\color{Purple}X = x_{i}}$ and $\large{\color{Purple}Y = y_{j}}$ be $\large{\color{Purple}n_{ij}}$
* Then 
 $$\large{\color{Purple}P(X=x_i ,Y=y_j)= \frac{n_{ij}}{N}}$$

* Where **N** is the total number of trials. So similarly you can ask what is probability of **basket is blue** and the ***fruit is apple***

$$\large{\color{Purple}
P(B=b , F=a)= \frac{45}{100} =0.45
}
$$

### Sum Rule
The **sum rule** asks the question which is, **if I do not want a joint probability but I simply want the question**
* What is the probability that the **basket is red** **(P(B=r)**)?
* What is the probability that the **fruit is an orange (P(F=o))**? 

The probability that the fruit is an orange is going to be **30** of the cases where the fruit was an orange and the basket was red, 15 of the cases where fruit was an **orange** and the **basket was blue**, which means a total of **45 cases**. So the probability that the fruit is an **orange** $\large{\color{Purple}P(F = O) = \frac{45}{100}}$

$$\large{\color{Purple}
\begin{align*}
& P(X = x_i)= \frac{c_i}{N} \ \ \ \ \  \Huge\textrm{ Marginal Probability} \\
 However, \\
 & c_i = \sum_{j} n_{ij}\\
 & \Rightarrow P(X=x_i)= \sum_{j} \frac{n_{ij}}{N} \ \ \ \ {\color{Black}[\frac{n_{ij}}{N} = P(X=x_i ,Y=y_j)]}\\
 & \Rightarrow \boxed{P \Big\(X=x_i \Big\)= \sum_{j} P\Big \(X=x_i ,Y=y_j\Big \)}   \ \ \ \ \  \Huge \textrm{ Sum Rule of Probability} \\
\end{align*}
}
$$

### Marginal Probability $\large{\color{Purple} P(X = x_i)}$
Now why is it called **marginal probability**? If you notice these numbers, these total numbers are written in the margin. That is the historical origin. Marginalization does not mean anything else, it simply means that the columns or the rows have been summed up and you have put them the total in the margin which is why the total probability is called the marginal probability.








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
P(W) P(w_1, w_2, w_3,\cdots ,w_n) \small{\color{Black}\cdots \cdots \cdots \cdots  \textbf{(1)}}
\end{equation}
}
$$

**Task:** To predict the next word using probability. Given the context, find the next word using

$$\large{\color{Purple} 
\begin{equation}
 P(w_n|w_1, w_2, w_3,\cdots ,w_{n-1})  \small{\color{Black}\cdots \cdots \cdots \cdots \textbf{(2)}}
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

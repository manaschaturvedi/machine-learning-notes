## Types of Machine Learning ##
Machine Learning can be classified into:
- Supervised
- Semi-supervised
- Unsupervised
- Reinforcement

## Supervised Learning ##
In supervised learning, the dataset is the collection of labeled examples { ( x <sub> i </sub> , y <sub> i </sub> ) } <sup> N </sup> <sub> i = 1 </sub>. Each element x <sub>i</sub> among N is called a feature vector. A feature vector is a vector in which each dimension j = 1, . . . , D contains a value that describes the example somehow. That value is called a feature and is denoted as x <sub>(j)</sub>. 

For instance, if each example x in our collection represents a person, then the first feature, x <sub>(1)</sub> , could contain height in cm, the second feature, x <sub>(2)</sub> , could contain weight in kg, x <sub>(3)</sub> could contain gender, and so on.

The label y <sub>i</sub> can be either an element belonging to a finite set of classes {1,2, . . . , C}, or a real number, or a more complex structure, like a vector, a matrix, a tree, or a graph.

The goal of a supervised learning algorithm is to use the dataset to produce a model that takes a feature vector x as input and outputs information that allows deducing the label for this feature vector.
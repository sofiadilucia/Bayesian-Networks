# Bayesian-Networks
**Learning the topology of a Bayesian Network from a database of cases using the K2 algorithm**

A **Bayesian belief-network** [1] structure is a directed acyclic graph in which nodes represent domain variables and arcs between nodes represent probabilistic dependencies [2]. Given a database of records, it is interesting to construct a probabilistic network that can provide insights into the probabilistic dependencies existing among the variables in the database. Such a network can be further used to classify future behavior of the modeled system [2]. 

Although researchers have made substantial advances in developing the theory and application of belief networks, the actual construction of these networks often remains a difficult, time-consuming task. An efficient method for determining the relative probabilities of different belief-network structures, given a database of cases and a set of explicit assumptions, is described in [2] and [3].

The K2 algorithm [3] can be used to learn the topology of a Bayes network [2], i.e. of finding the most probable belief-network structure, given a database.
- **Part 1** After having studied the problem in the suggested literature ([2]-[3]), Implement the algorithm in R and check its performances with the test data set given in [3]: Ruiz, Asia and Child data sets.
- **Part 2** Implement and test the K2 algorithm with the test data sets ([3]). Compare the results with that obtained with the bnstruct R library [4]

## Bibliography
[1]: **Bayesian Networks**: (Link to relevant paper or article) <br>
[2]: **A Bayesian Method for the Induction of Probabilistic Networks from Data**: ([Link](https://link.springer.com/article/10.1007/BF00994110#Bib1)) <br>
[3]: **Illustration of the K2 Algorithm for learning Bayes Net Structures**: ([Link](https://web.cs.wpi.edu/~cs539/s05/Projects/k2_algorithm.pdf)) <br>
[4]: **bnstruct: an R package for Bayesian Network structure learning in the presence of missing data**: ([Link](https://academic.oup.com/bioinformatics/article/33/8/1250/2730229)) <br>
[5]: **bnstruct: an R package for Bayesian Network Structure Learning with missing data**: ([Link](https://cran.r-project.org/web/packages/bnstruct/vignettes/bnstruct.pdf)) <br>

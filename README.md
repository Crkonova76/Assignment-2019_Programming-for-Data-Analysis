# Assignment-2019_Programming-for-Data-Analysis

__GMIT 2019
Martina Crkonova__

#### Purpose of this assignment is to explain the purpose and usage of numpy.random package in Python

The Jupyter notebook is used to complete the assignment.The Jupyter Notebook is an open-source web application that allows to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.

_Source:_
>https://jupyter.org/

Numpy is a library that is used for computing scientific/mathematical data. Other usages are in:

*Numerical Analysis
*Linear algebra
*Matrix computations

NumPy is an open source Python package for scientific computing. NumPy supports large, multidimensional arrays and matrices. NumPy is written in Python and C.

_Source:_
>https://www.quora.com/In-Python-what-is-NumPy-How-is-it-used

## Definitions

### Numpy terminology

#### Axis/axes

Dimension is defined as the minimum number of coordinates needed to specify any point within a space. In Numpy dimensions are called axes.The number of axes is rank.

 * ndarray.ndim - num of axes, definition of dimension<br/>
 * ndarray.shape - describes how many data (range) along each available axis<br/>
 * ndarray.size - provides the total number of elements of the array<br/>
 * ndarray.dtype - an object describing the type of elements in array <br/>
 * ndarray.itemsize - the size in bytes of each element of the array<br/>
       
### Statistics terms:

#### Mean

The statistical mean refers to the mean or average that is used to derive the central tendency of the data in question. It is determined by adding all the data points in a population and then dividing the total by the number of points. The resulting number is known as the mean or the average.

_source:
>https://www.techopedia.com/definition/26136/statistical-mean


#### Standard deviations

The Standard Deviation is a measure of how spread out numbers are.
Its symbol is σ (the greek letter sigma)

![Satndard deviation formula](https://user-images.githubusercontent.com/47481671/68548931-3551b800-03ea-11ea-994a-5db24ba3e243.png)

&sigma = standard deviation<br/>
&mu = mean<br/>
N = how many values<br/>
Xi = individual value


_source:_
>https://www.mathsisfun.com/data/standard-deviation.html

### Random Variable

A random variable is a set of __possible values__ from a random experiment.

* possible outcomes of a variable are RANDOM numerical outcomes
* types of random variable:
a, Discrete random variables-take on only a countable number of distinct values,can be quantified
b, Continues random variable -the functions that take on continuous values



### Permutation

A permutation is an arrangement of all or part of a set of objects, with regard to the order of the arrangement.<br/>
Formula for the number of permutations of n objects taken r at a time:<br/>

![Permutation formula](https://user-images.githubusercontent.com/47481671/68549013-667eb800-03eb-11ea-9b73-2071018d6ccc.PNG)

_source:_
>https://stattrek.com/statistics/dictionary.aspx?definition=permutation

### Combination

A combination is a selection of all or part of a set of objects, without regard to the order in which objects are selected.
Formula for the number of combinations of n objects taken r at a time:<br/>

_source:_
>https://stattrek.com/statistics/dictionary.aspx?definition=combination

### Probability distributions

* Provides the probabilities of the occurence of various possible outcomes in an experiment


#### Uniform Distribution

_source:_
>https://www.datacamp.com/community/tutorials/probability-distributions-python

The probability distribution function of the continuous uniform distribution is:




The curve describing the distribution is a rectagle with constant heigh across the interval and 0 heigh elserwhere.Any interval of numbers of equal width has an equal probability of being observed.





#### Normal Distribution (Gaussian distribution)

_source:_
>https://www.datacamp.com/community/tutorials/probability-distributions-python

A normal distribution has a bell-shaped density curve described by its mean μ and standard deviation σ. The density curve is symmetrical, centered about its mean, with its spread determined by its standard deviation showing that data near the mean are more frequent in occurrence than data far from the mean. The probability distribution function of a normal density curve with mean μ and standard deviation σ at a given point x is given by:



The graph below describes what the distribution looks like:



#### Poisson Distribution

_source:_
>https://www.datacamp.com/community/tutorials/probability-distributions-python

Poisson random variable is typically used to model the number of times an event happened in a time interval. For example, the number of users visited on a website in an interval can be thought of a Poisson process. Poisson distribution is described in terms of the rate (μ) at which the events happen. An event can occur 0, 1, 2, … times in an interval. The average number of events in an interval is designated λ (lambda). Lambda is the event rate, also called the rate parameter. The probability of observing k events in an interval is given by the equation:



The following graph shows typical poisson distribution:



Note that the normal distribution is a limiting case of Poisson distribution with the parameter λ→∞. Also, if the times between random events follow an exponential distribution with rate λ, then the total number of events in a time period of length t follows the Poisson distribution with parameter λ 
#### Exponential Distribution

_source:_
>http://wiki.stat.ucla.edu/socr/index.php/AP_Statistics_Curriculum_2007_Pareto

Pareto distribution is a skewed, heavy-tailed distribution that is sometimes used to model that distribution of incomes. The basis of the distribution is that a high proportion of a population has low income while only a few people have very high incomes.


#### Binomial Distribution

_source:_
>Learning Scientific Programming with Python By Christian Hill 

* Describes the numbers of particular outcomes in a sequence of n Bernoulli trials  (n independent experiments, each of which can yied exactly two possible outcomes 
* Each outcome has a fixed probability ,the same from trial to trial
* if the probability of a single particular outcome is p, the probablity that such a sequence of trials yields exactly k such outcomes is




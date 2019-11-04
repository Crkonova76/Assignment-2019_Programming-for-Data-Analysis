# Assignment-2019_Programming-for-Data-Analysis

## Definitions



### Numpy terminology

#### Axis/axes

Dimension is defined as the minimum number of coordinates needed to specify any point within a space. In Numpy dimensions are called axes.The number of axes is rank.

       ndarray.ndim #num of axes, definition of dimension
       ndarray.shape #describes how many data (range) along each available axis
       ndarray.size #provides the total number of elements of the array
       ndarray.dtype #an object describing the type of elements in array 
       ndarray.itemsize #the size in bytes of each element of the array
       
       

### Probability distributions

* Provides the probabilities of the occurence of various possible outcomes in an experiment

#### Random Variable

* possible outcomes of a variable are RANDOM numerical outcomes
* types of random variable:
a, Discrete random variables-take on only a countable number of distinct values,can be quantified
b, Continues random variable -the functions that take on continuous values


#### Uniform Distribution

Source: https://www.datacamp.com/community/tutorials/probability-distributions-python

The probability distribution function of the continuous uniform distribution is:




The curve describing the distribution is a rectagle with constant heigh across the interval and 0 heigh elserwhere.Any interval of numbers of equal width has an equal probability of being observed.





#### Normal Distribution (Gaussian distribution)

Source: https://www.datacamp.com/community/tutorials/probability-distributions-python

A normal distribution has a bell-shaped density curve described by its mean μ and standard deviation σ. The density curve is symmetrical, centered about its mean, with its spread determined by its standard deviation showing that data near the mean are more frequent in occurrence than data far from the mean. The probability distribution function of a normal density curve with mean μ and standard deviation σ at a given point x is given by:



The graph below describes what the distribution looks like:



#### Poisson Distribution

Source: https://www.datacamp.com/community/tutorials/probability-distributions-python

Poisson random variable is typically used to model the number of times an event happened in a time interval. For example, the number of users visited on a website in an interval can be thought of a Poisson process. Poisson distribution is described in terms of the rate (μ) at which the events happen. An event can occur 0, 1, 2, … times in an interval. The average number of events in an interval is designated λ (lambda). Lambda is the event rate, also called the rate parameter. The probability of observing k events in an interval is given by the equation:



The following graph shows typical poisson distribution:



Note that the normal distribution is a limiting case of Poisson distribution with the parameter λ→∞. Also, if the times between random events follow an exponential distribution with rate λ, then the total number of events in a time period of length t follows the Poisson distribution with parameter λt.


#### Exponential Distribution

Source: https://www.datacamp.com/community/tutorials/probability-distributions-python

The exponential distribution describes the time between events in a Poisson point process, i.e., a process in which events occur continuously and independently at a constant average rate. It has a parameter λ called rate parameter, and its equation is described as :


A decreasing exponential distribution looks like :




#### Binomial Distribution

source:Learning Scientific Programming with Python By Christian Hill 

* Describes the numbers of particular outcomes in a sequence of n Bernoulli trials  (n independent experiments, each of which can yied exactly two possible outcomes 
* Each outcome has a fixed probability ,the same from trial to trial
* if the probability of a single particular outcome is p, the probablity that such a sequence of trials yields exactly k such outcomes is



source:Learning Scientific Programming with Python By Christian Hill 
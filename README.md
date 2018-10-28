# SCIT-Task

Following libraries are imported for the task

* Numpy
* Matplotlib

## Question 1

 In this task, 1000 samples are generated using numpy.random.poission() for 3 times and their histograms are plotted.
 
 ### Histogram - Random Poisson Graphs 
 
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/a_poisson.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/b_poisson.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/c_poisson.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/abc_poisson.png)

Mean value for poisson distribution is 100. The probabily is higher when x values approaches the mean. The skewness of the graph are neither positive or negative.

## Question 2

 In this task, 1000 samples are generated using numpy.random.normal() for 3 times and their histograms are plotted.
 
 ### Histogram - Random Normal Graphs 
 
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/d_normal.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/e_normal.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/f_normal.png)
![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/def_normal.png)

Mean value for normal distribution is 100. The skewness of the graph are neither positive or negative.

## Question 3

In this task, average of random 100 samples is taken from the 1000 samples without replacing, repeatedly for 100 times. The average 100 averages are then plotted as histograms for both poisson and normal distribution.

 ### Histogram - Average of 100 samples in Poisson distribution
 
  ![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/abc_poisson_average.png)


 ### Histogram - Average of 100 samples in Normal distribution
 
  ![picture](https://github.com/d4rshik/SCIT-Task/blob/master/SCIT/plots/def_normal_average.png)

The mean and standard deviation for this graph is 100 and 1 (default scale). Here in the different distributions of both poission and normal we can see that the mean and the average are similar.

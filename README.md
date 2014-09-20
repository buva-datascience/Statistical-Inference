  
**Important Note:** *Kindly visit the below link for an updated report for this Course Project Assessment. 
[Link to my Simulation Report](http://rpubs.com/bram/StatInf-Proj1-Simulation)
[Link to my Inference Report](http://rpubs.com/bram/StatInf-Proj2-Inference)
[Link to my Reproducible Research Repository](https://github.com/buva-datascience/Statistical-Inference)*  
  
## Introduction  

This is the project for the statistical inference class. In it, we will use simulation to explore inference and do some simple inferential data analysis. The project consists of two parts:

1. Simulation exercises.
2. Basic inferential data analysis.

A report is created to answer the questions for each of the Exercise.  
  
# 1. Simulation Exercise  
  
The exponential distribution can be simulated in R with rexp(n, lambda) where lambda is the rate parameter. The mean of exponential distribution is 1/lambda and the standard deviation is also also 1/lambda. Set lambda = 0.2 for all of the simulations. In this simulation, you will investigate the distribution of averages of 40 exponential(0.2)s. Note that you will need to do a thousand or so simulated averages of 40 exponentials.

Illustrate via simulation and associated explanatory text the properties of the distribution of the mean of 40 exponential(0.2)s.  You should
1. Show where the distribution is centered at and compare it to the theoretical center of the distribution.
2. Show how variable it is and compare it to the theoretical variance of the distribution.
3. Show that the distribution is approximately normal.
4. Evaluate the coverage of the confidence interval for 1/lambda: X¯±1.96Sn√.  
   
  
# 2. Basic Inferential Data Analysis  
  
Now in the second portion of the class, we're going to analyze the ToothGrowth data in the R datasets package. 
Load the ToothGrowth data and perform some basic exploratory data analyses 
Provide a basic summary of the data.
Use confidence intervals and hypothesis tests to compare tooth growth by supp and dose. (Use the techniques from class even if there's other approaches worth considering)
State your conclusions and the assumptions needed for your conclusions.   
  
  
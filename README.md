# Advanced Statistic Methods in Physics

This repository hosts my solved exercises and exam preparations. Here I will give an overview over the files and exercises and where to find different topics

## Topics

The corresponding exercise sheets is given in the brakets.

- Bayesian inference (2, 3)
- Simulating data (3, 5)
- Linear models (4, 5)
- Categorical varaiables (5, 7, 9)
- Comparing models (5, 6, 7, 11, 12)
- Multivariate models (6, 7, 9, 12)
- Multicollinearity (6)
- Interacting multivariate models (9)
- General linear models (10, 11)
    - Binomial (10)
    - Poisson
- Multi-level models (11, 12)
- GLMs error handling

## Exercise sheet 2

This discusses Bayesian inference.

## Exercise sheet 3

In these exercises we continue the discussion of Bayesian inference and then simulate an experiment (globe tossing).

## Exercise sheet 4

This sheet concerns itself with linear models, sampling the posterior distribution, comparing models, log scales.

## Exercise sheet 5

Introducing categorical variables to the linear models, building and comparing models, and simulating experiments.

## Exercise sheet 6

In this exercise we look at multivariate models for the first time with the example of the red foxes data set. We build different models and compare them, including different predictors. We encounter multicollinearity when including interdependent predictors such as the average food per area and the size of the area.

## Exercise sheet 7

We continue constructing multivariate models, this time looking at primates, where we investigate the size of the neocortex in dependence of the energy content of their milk. We look at different clades and use categorical variable to discuss the differences there.

## Exercise sheet 8

This exercise introduces the notion of training and testing datasets. Using the Watanabe–Akaike information criterion we compare the models, adding it to our toolbox.

- [x] Out of sample deviance needs to be investigated further.

## Exercise sheet 9

In this exercise sheet we continue our discussion of categorical variables, where we now look at them in multivaraiate models. We look at the example of wine tasting.

## Exercise sheet 10

This exercise introduces the general linear models for the first time and we consider an example of grands being awarded - a binomial process. The binomial glm requires the logit function to map the linear model to the probability space.

- [ ] In a further step we may also consider the posson distributed glm, which would require the log as a mapping function. It gets introduced in lecture 10.

## Exercise sheet 11

Multi-level glm get introduced in this exercise. The mulit-level approach allowes us to control for over-dispresion and increase the uncertainty towards its real value. We consider two examples, one of tadpoles in 48 tanks, and one for salamanders on 47 sites.

## Exercise sheet 12

Here we continue our discussion of multivariate models. We can make use of the multi-level approach, which in this case is not that helpful. The example tihis time is a exoplanets dataset, where we investigate the dependence of the density on a handful of parameters.

## Exercise sheet 13

This sheet continues the investigation of the exoplanets dataset with the inclusion of errors.

- [ ] Solve an example with errors that is not exoplanets. This is explained in lecture 
---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 V2               <br/>
**Topic**:  Statistics <br/>
**Amount of time**:  60 minutes  <br/>
**Author**: Laura Colon-Melendez

***

#### Lesson Summary:

The lesson starts by commenting on the assumptions that are needed when performing parametric statistical tests like t-tests to motivate the use of permutation tests, where the distribution of the test statistic under the null hypothesis is constructed rather than assumed. An exact permutation test is performed guiding students step by step along the way. This leads to a discussion on what happens when sample sizes are too large and there are too many permutations of the samples to consider. Monte Carlo simulations are used to sample from the permutation space in a coding exercise with starter code that students fill out. Next, students use bootstrap sampling to perform a one-sample and two-sample hypothesis test

#### Topic:

Statistics / Resampling Methods

#### Learn.co material:

[Resampling Methods](https://github.com/learn-co-curriculum/dsc-resampling-methods)

[Resampling Methods - Lab](https://github.com/learn-co-curriculum/dsc-resampling-methods-lab)

[Monte Carlo Simulations](https://github.com/learn-co-curriculum/dsc-monte-carlo-simulations)

[Monte Carlo Simulations - Lab](https://github.com/learn-co-curriculum/dsc-monte-carlo-simulations-lab)


#### Prerequisite knowledge:

* Students should be able to set null and alternative hypotheses. 
* Students should be able to perform z-tests and t-tests using Python. 
* Students should know how to use numpy to draw samples with replacement. 

#### Prerequisite Learn.co material:

[P-Values and the Null Hypothesis](https://github.com/learn-co-curriculum/dsc-p-values-and-null-hypothesis)

[Conducting T-Tests](https://github.com/learn-co-curriculum/dsc-t-tests)

[Two Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-two-sample-t-tests-lab)

#### Learning goals for this lesson:

* Students can perform an exact permutation test using python.
* Students can perform a simulated permutation test using Monte Carlo simulations using python.
* Students can perform one-sample tests using bootstrapping of samples. 

#### Relevant learning goals from Airtable: 

* MONTE_CARLO.1.rec2f0eltYt7w297V
* MONTE_CARLO.1.recpVdhyzG35deRxU
* MONTE_CARLO.2.recxJTyWmk03rHfK3
* MONTE_CARLO.1.rec6pyy2hbwgBkC10
* MONTE_CARLO.2.rec2YqSI5hTO8Tms2

#### Misconceptions / Notes

Setting up one-sided vs two-sided tests can be confusing; spend time clarifying this when discussing the exact permutation test example.

#### Materials
- Ipython notebook 

#### Vocab / Concepts 

* permutation test
* bootstrapping 

#### Lesson Outline:

* Brief into to resampling methods (<5 minutes)
* Exact permutation tests (15 minutes)
    * Students should perform a two-sided test in this case. 
* Monte Carlo Simulation of Permutation tests (15 minutes) 
    * It's important to motivate the need for sampling the permutation sample space: sometimes we don't have enough computing power to perform an exact permutation test. 
* Bootstrapping: One-sample test (15 minutes)
* Summary (5 minutes) 

Wiggle room: 5 minutes

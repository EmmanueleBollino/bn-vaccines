# Bayesian network for COVID-19 vaccines adverse reactions
### *Fundamentals of Artificial Intelligence and Knowledge Representation - Module 3*
#### *Alma Mater Studiorum Università di Bologna - a.a 20/21*

##### **Author:** [Emmanuele Bollino](https://www.linkedin.com/in/emmanuele-bollino/)

> **WARNING** All the data used in this project are taken from the [VAERS](https://wonder.cdc.gov/vaers.html) database managed by [CDC](https://www.cdc.gov/).
>
> This project is intended for research purposes only. CDC reserves all the rights for these data.

> Data files are not included in this repo due to CDC policies.

## Abstract
This project was developed in June 2021 during the COVID-19 outbreak. In this period the governments from all around the world
are doing massive vaccination campaigns. There are several manufacturers of vaccines, and some people are facing with
side effects caused by vaccine injections. Most of the side effects are self solving but in this period there is an
open debate about the safety of these vaccines.

This project deals with vaccine adverse events reported in the U.S.A. on the [VAERS](https://wonder.cdc.gov/vaers.html)
database that contains the adverse events of vaccines in the U.S.A. from 1990.

The aim of this project is to study the correlation between some factors and the gravity of the adverse events of COVID-19
vaccines. Given some risk-factors and other information about the injection, we want to determine the probability of
having a serious adverse reaction. Because of the lack of non-adverse events, all the considerations are done considering
that the patient has for sure an adverse reaction.

For the sake of simplicity, data contained in the database have hardly been simplified, loosing important information
about the domain. Because of this, the results are considered over simplistic and not reliable. This project only shows
that using probabilistic graphical models for this domain is possible.

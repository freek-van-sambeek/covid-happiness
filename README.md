# COVID-19 & Happiness
This repository contains the task file for the 2023 Python for Economics week project about finding the causal effect of COVID-19 cases on the average sentiment of tweets in the UK.

## Introduction
As policy-making during an epidemic is all about making economic tradeoffs, one would like to quantify the gains and losses in the factors a government is is trading off between. The trade-offs to monetary factors and other classical economic factors are well documented, of course. However, the social costs of viral cases less so (among other forms of social costs involved in a pandemic). One may make an attempt to quantify the social costs of the number of cases of such a virus in your country by looking at the causal effect of COVID-19 cases on the average sentiment of how people express themselves online.

## Overview Project
In this project the main goal is to run a regression of the number of COVID-19 infections on the average sentiment of how people express themselves online. You will start by carrying out this analysis for the UK. A clear confounder here are government restrictions to curb the spread of the virus. You will control for this confounder in the regression alongside time-fixed effects that deal with the biases caused by new ways of measuring cases, changes in testing accuracy and availability, among other possible biases.
</br></br>
To be able to run this final regression, though, you will need to collect the data. This notebook will walk you through the steps associated with this and the final step of running the regression.

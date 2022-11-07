# Bradley-Terry-Model-for-NCAA

The code in this appendix is working on building statistical analysis based on the win-loss data for NCAA Division 1 men’s basketball teams during 2021-2022 season. The goal of this project aims at helping people better understand the teams. 

first of all, we will build a _plain-vanilla Bradley-Terry model_, as well as a version of the model using a penalized form of the _Bayesian generalized linear regression_ model. On the next step, we will build other models, which could account for home advantage, and allow for teams’ strength changes over the season. After that, the _cross-validation_ will be used to choose a preferred model that fits best among 4 models. 

We will then finally show the rank result of the model and prove the uncertainty of the model by hypothesis test on the difference of two teams’ fitted ability coefficients.

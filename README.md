# Credit-Risk-Modelling

Credit risk modeling is a technique used by lenders to determine the level of credit risk associated with extending credit to a borrower. There are two main classes of credit risk
models – structural and reduced form models. Structural models are used to calculate the probability of default for a firm based on the value of its assets and liabilities. The objective of this project is to model a credit risky portfolio of corporate bonds. The structural model is used to infer a counterparty’s (CP) one year in future credit state.

Since the true distribution of losses is not known, we simulate standard normal random variables for systemic and idiosyncratic components many times and assume it as the true distribution. Following that, to check if a smaller sample could represent the true distribution, we consider generating samples of 5000 in two methods as follows:
1. 1000 systemic scenarios for 5 idiosyncratic scenarios (1000x5=5000) termed as in sample MC1.
2. 5000 systemic scenarios for 1 idiosyncratic scenarios (5000x1=5000) termed as in sample MC2.

Model error and sampling errors are calculated to evaluate the simulations thus generated




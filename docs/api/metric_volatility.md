# Metric Volatility

The aim of this module is analysis of how well a model performs on a given dataset, and how stable the performance is.

The following features are implemented:

- **TrainTestVolatility** - Estimation of volatility of metrics. The estimation is done by splitting the data into train and test multiple times and training and scoring a model based on these metrics.

  - **SplitSeedVolatility** - Estimates volatility of metrics based on splitting the data into train and test sets multiple times randomly, each time with different seed.

  - **BootstrappedVolatility** - stimates volatility of metrics based on splitting the data into train and test with static seed, and bootstrapping train and test set.


::: probatus.metric_volatility.volatility

### Spatio-temporal Neural Networks for Space-Time Series Forecasting

-----------

## Intro - Time series difficulties
- Reducing the dimensionality and uncovering the underlying data generation process naturally leads to consider latent dynamic models.

- STNN(Spatio-temporal neural network) : captured the dynamics and correlations in multiple series at the spatial and temporal levels.
=> Model captures the spatio-temporal dynamics of the process into latent states.
=> then decoding the latent space into actual series observations.

## Related works

- parametric generative modes -> popular research topics
: Stochastic Gradient Variational Bayes algorithms

- Gaussian markov random fields

: Domain for spatio-temporal -
: Brain Computer Interface (BCI)

## Model

1) Model captures the dynamics of process to latent space
2) from Latent factors to prediction of the actual series

: Latent factors are learnable parameters
: In a loss funtion - Z(t) , Z(t+1) MAE calculation => Latent Factors's Dynamics

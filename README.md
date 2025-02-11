# Project 5: Simulation Studies and Statistical Models
This project encompasses several simulation-based analyses to explore statistical concepts such as the Central Limit Theorem (CLT), binomial probability estimation, the exponential distribution, and AR(1) models.

# Key Analyses & Insights:
### Central Limit Theorem (CLT) Simulation:

A simulation study was conducted to demonstrate the CLT by generating 1000 samples from a Poisson distribution with a mean of 10. The sample means were standardized and plotted against the theoretical standard normal distribution. The results confirmed the CLT, as the empirical cumulative distribution function (ECDF) closely matched the theoretical CDF of a standard normal distribution.

### Dice Probability Simulation:

A simulation was used to estimate the probability of achieving at least a certain number of sixes when tossing six, twelve, or eighteen fair dice. For each case (a, b, and c), a function simulated 1000 tosses of dice, and the probability of success was computed. The results revealed that proposition (a) (tossing six dice and getting at least one 6) had the highest probability of success.

### Exponential Distribution:

A function was written to generate random draws from an exponential distribution using the inversion method. A sample of size 1000 was drawn, and the resulting histogram was overlaid with the theoretical exponential probability density function (PDF). This provided a visual comparison between the simulated data and the theoretical distribution.

### AR(1) Model Simulation:

A simulation study was conducted to assess how accurate two variance approximation formulas are for an AR(1) model with different lags (h = 1, 5, and 10). Functions were written to simulate AR(1) time series data, compute autocorrelations, and apply variance approximation formulas. The results showed the accuracy of the approximations, providing insights into their reliability for modeling AR(1) processes.

# Main Takeaways:
**Central Limit Theorem:** The simulation confirmed that the distribution of the sample means tends to a normal distribution as per the CLT.

**Dice Probability:** Proposition (a) (with six dice and at least one 6) was found to have the highest probability of success among the three propositions.

**Exponential Distribution:** The generated data from the exponential distribution closely matched the theoretical PDF, confirming the correctness of the simulation method.

**AR(1) Models:** The simulation provided a comparison of different variance approximation formulas, showing their performance in estimating variances for AR(1) models with different lag values.

# Conclusion:
The project effectively demonstrates various statistical concepts using simulations. From confirming the CLT to evaluating dice probabilities and time series models, the simulations provided valuable insights into the practical application of these statistical theories.

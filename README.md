# Demonstration-of-the-Expectation-Maximization-Principle

In statistics, an expectation–maximization (EM) algorithm is an iterative method to find (local) maximum likelihood or maximum a posteriori (MAP) estimates of parameters in statistical models, where the model depends on unobserved latent variables. The EM iteration alternates between performing an expectation (E) step, which creates a function for the expectation of the log-likelihood evaluated using the current estimate for the parameters, and a maximization (M) step, which computes parameters maximizing the expected log-likelihood found on the E step. These parameter-estimates are then used to determine the distribution of the latent variables in the next E step.

Finding a maximum likelihood solution typically requires taking the derivatives of the likelihood function with respect to all the unknown values, the parameters and the latent variables, and simultaneously solving the resulting equations. In statistical models with latent variables, this is usually impossible. Instead, the result is typically a set of interlocking equations in which the solution to the parameters requires the values of the latent variables and vice versa, but substituting one set of equations into the other produces an unsolvable equation.

# Applications of the EM algorithm:

EM is frequently used for data clustering in machine learning and computer vision. In natural language processing, two prominent instances of the algorithm are the Baum–Welch algorithm for hidden Markov models, and the inside-outside algorithm for unsupervised induction of probabilistic context-free grammars.

EM is frequently used for parameter estimation of mixed models, notably in quantitative genetics.

In psychometrics, EM is almost indispensable for estimating item parameters and latent abilities of item response theory models.

With the ability to deal with missing data and observe unidentified variables, EM is becoming a useful tool to price and manage risk of a portfolio.

The EM algorithm (and its faster variant ordered subset expectation maximization) is also widely used in medical image reconstruction, especially in positron emission tomography, single photon emission computed tomography, and x-ray computed tomography. See below for other faster variants of EM.

In structural engineering, the Structural Identification using Expectation Maximization (STRIDE) algorithm is an output-only method for identifying natural vibration properties of a structural system using sensor data (see Operational Modal Analysis).

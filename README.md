# Bayesian_Inference_of_a_Contact_Network

A machine learning scheme was developed utilizing a Boltzmann machine, which was optimized through a Metropolis-Hastings algorithm (a Markov Chain Monte Carlo method). This approach was specifically designed for inferring the properties of variables and coupling matrices from a given dataset, data.dat. Subsequent to deriving these matrices, their Frobenius norms were calculated and compared with the true interaction graph in groundtruth.dat.

The project included an exhaustive descriptive and visual analysis to deepen the understanding of both the data and the model’s performance. Furthermore, the original Boltzmann machine was enhanced by incorporating a Prior Distribution, allowing for an assessment of the Bayesian approach's efficacy compared to the initial model.

In the final stages, upon achieving convergence with the Boltzmann Machines, a Monte Carlo sampling process was employed. This step was critical for evaluating the auto-correlation function of the samples, with a particular focus on its variation in response to changes in the number of observations and the waiting time.

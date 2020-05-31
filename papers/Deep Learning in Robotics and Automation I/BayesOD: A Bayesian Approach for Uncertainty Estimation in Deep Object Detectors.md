- goal is to estimate the predictive uncertainty in object detectors, so that they could be used as sensors in robotic system
- uncertainty could be quantified as the probability distribution of the object class and the bounding box corners
- problem formulation
![](assets/aa9f43ae.png)
- network architecture
![](assets/fa8022d4.png)
- covariance regression, the highlighted term cannot be modeled since we do not have groundtruth covariance   
![](assets/f9eb3383.png)
- to ensure sigma is PSD, force the network to learn the following
![](assets/88332ccf.png)
- then the loss becomes
![](assets/4a3e6458.png)
- finally use Bayesian inference to get the distribution
![](assets/7edea50e.png)
- future works
![](assets/774faf48.png)

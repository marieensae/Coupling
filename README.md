## Simulation and Monte Carlo

You must form a group of three students among your TD class, select one of the following projects, and do it by the last TD class, where you will do an oral presentation of your results in front of the other students. You may return a document with your plots and results to your “chargé(e) de TD” (no need to return a formal report). Please make sure you also send your code.
Important: Always make sure you have assessed in some way the numerical error of your estimates (e.g. through box-plots over repeated runs for instance).
Bonus questions are optional: do them when are confident you treated properly the previous points.
It’s ok to look up online for solutions (and adapt code you found on the internet), but cite your sources accordingly.
If you are stuck, feel free to get in touch with your “chargé(e) de TD”, who will let me know.

# Coupling

Given two probability distribution, p and q, we are interested in constructing a joint distribution (coupling) for (X, Y ), such that X ∼ p, Y ∼ q, and P(X = Y ) with high probability. 
The following paper: https://arxiv.org/abs/2201.09585 proposes such a construction, and shows it may be applied to two multivariate Gaussian distributions (with different covariance matrices).
This project consists in implementing the proposed approach, and compare it to the simpler approach known as Thoriston’s algoritm (Appendix I in the paper). Explain why the latter approach is valid, and is related to rejection sampling. You can consider different problems, of increasing dimension. Notice that the running time of these algorithms is random, comment on the corresponding distributions.
Bonus: If time permits, you may try to understand how you may use such coupling inside a random walk Metropolis, and replicate the experiments in Section 5.3.
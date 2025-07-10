# NMN-tomo
Jupyter notebook to obtain the results of the paper: Multi-time quantum process tomography on a superconducting qubit, https://doi.org/10.48550/arXiv.2308.00750

Tomography: The code uses the experimental data provided in the two .json files and constructs the full process matrix for 10 data points. Intermediate process matrices (experimental (non-physical), physical and Markovian are saved on Ws).

Metrics: The code calculates Relative Entropy and Negativity as a measure of general and quantum non-Markovian noise respectively for the 10 data points. The data are saved on file Ws. The data are reported on the paper on Table 1.

Figures: The code produces the cityscapes of Figure 3 on the paper.

Simulation: The code produces the simulation figures of the Appendix, Figure 5.

Error bars: We use the bootstraping technique to calculate error bars that account for the sampling error.

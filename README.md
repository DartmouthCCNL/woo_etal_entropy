## Overview
This repository contians custom simulation and analysis codes for Woo et al., 2025 Entropy

Requires installation of MATLAB 2021b or higher. Some functionality might not work for earlier version. The following codes have been tested in MATLAB version 2021b and 2022b. See [here](https://www.mathworks.com/help/install/install-products.html) for more instuctions on the installation.

## Directories
* _**info_metrics_func**_: contains functions for computing information-theoretic measures based on conditional entropy and (normalized) mutual information
* **_RL_models_func_**: contains reinforcement learning model scripts
* **_sim_func_**: contains codes needed for model simulations
* **_decoding_func_**: contains functions related to binary decoding of positivity bias
* **_helpers_**: contains miscellaneous helper functions

## How to use
Each script in the root directory corresponds to each section of the manuscript, as follows.

`Sim0_example_metrics`: Figure 2, showing schematic of an RL agent performing a probabilistic reversal learning task, with behavioral quantification using information-theoretic metrics.
`Sim1_positivity_bias`: Figure 3 in Section 3.1, showing behavioral signatures of positivity bias and its decoding using information-theoretic metrics.
`Sim2_metaplasticity`: Figure 4 in Section 3.2, comparing plastic and metaplastic models and their distinct predictions on information-theoretic metrics.
`Sim3_global_reward`: Figure 5 in Section 3.3., showing model with modulation of stay/switch strategy by global reward rate, and its distinct predictions on information-theoretic metrics compared to standard RL.
`Sim4_multidimensional`: Figure 6-7 in Section 3.4, showing distinct predictions of information-theoretic metrics for adopting and arbitrating between alternative strategies in a multidimensional reward environment.

For further questions, please contact jae.hyung.woo.gr@dartmouth.edu






# Renyi2-Entropy-Qiskit
Calculation of second-order Renyi entropy using Qiskit for quantum spin systems.

## Overview

This repository contains Python code for calculating the second-order Rényi entropy of quantum spin systems using Qiskit.

The Rényi-2 entropy of a subsystem A is defined as

$$
S_A^{(2)} = -\ln \left[\mathrm{Tr}(\rho_A^2)\right]
= -\ln \left[\frac{1}{8}\sum_{P\in\mathcal{P}_3}
\langle P\rangle^2\right],
$$

where $$\(\rho_A\)$$ is the reduced density matrix of subsystem A, and $$\langle P\rangle$$ is the expectation value of Pauli string operators 


## Methodology

The calculation involves:

1. Preparing an initial quantum state.
2. Constructing the quantum circuit for time evolution.
3. Computing the reduced density matrix of a selected subsystem.
4. Evaluating the subsystem purity.
5. Calculating and plotting the second-order Rényi entropy.

## Requirements

- Python
- NumPy
- Qiskit
- Matplotlib
- Jupyter Notebook

## Installation

```bash
pip install qiskit numpy matplotlib jupyter
```

## Usage

Open `Renyi2_vs_time_NA3_with_ODR_factor_New_Formula_SA_GitGub.ipynb`, `Renyi2_vs_time_NA3_NA2_with_ODR_factor_New_Formula_SA_GitHub.ipynb`, `Renyi2_vs_time_NA3_NA1_with_ODR_factor_New_Formula_SA_GitHub.ipynb` in Jupyter Notebook and execute the cells sequentially.

To plot Renyi2 entropy versus system size N for different sub-system size $$N_A =1,2,3$$ open `S2_V2_vs_N_plots_SIMULATOR_result_withErrorbar_toSimulator_StdError_V3_SORTED_odr.ipynb` in Jupyter  Notebook and execute the cell one after another.

## Author
* Jiunn-Wei Chen,
* Yu-Ting Chen,
* Ghanashyam Meher ,
* Berndt Müller, 
* Andreas Schäfer,
* Xiaojun Yao

## Reference

Jiunn-Wei Chen et al., *Local Thermalization of SU(2) Lattice Gauge Fields on Quantum Computers*, arXiv:2603.23948v4.


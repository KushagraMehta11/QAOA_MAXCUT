# Max-Cut Problem and Traveling Salesman Problem Optimizers

This repository contains two Jupyter notebooks that explore optimization techniques for solving the Max-Cut problem using different optimizers. The Max-Cut problem is a classic combinatorial optimization problem, and these notebooks apply different strategies to find solutions efficiently.

## Table of Contents

- [Overview](#overview)
- [Notebooks](#notebooks)
  - [max_cut_ADAM_optimizer.ipynb](#max_cut_adam_optimizeripynb)
  - [max_cut_IPG_optimizer.ipynb](#max_cut_ipg_optimizeripynb)
- [Requirements](#requirements)


## Overview

The Max-Cut problem involves partitioning the vertices of a graph into two subsets such that the number of edges between the two subsets is maximized. This repository provides implementations using two different optimization techniques:

1. **ADAM Optimizer**: A gradient-based optimization method widely used in training deep learning models.
2. **Interior Point Gradient (IPG) Optimizer**: A method designed for handling constraints in optimization problems.

These notebooks demonstrate the application of these techniques to solve the Max-Cut problem, showcasing different approaches to tackle this NP-hard problem.

## Notebooks

### max_cut_ADAM_optimizer.ipynb

This notebook applies the ADAM optimizer to the Max-Cut problem. It involves:

- Defining the Max-Cut problem for a given graph.
- Setting up the ADAM optimizer to iteratively improve the cut value.
- Visualizing the results and the convergence of the optimizer.

### max_cut_IPG_optimizer.ipynb

This notebook implements the Interatively Pre-Descent Gradient (IPG) optimization technique for the Max-Cut problem. It covers:

- Formulating the Max-Cut problem in a way that can be tackled by the IPG optimizer.
- Implementing the IPG algorithm to optimize the cut value under specific constraints.
- Analyzing the performance and comparing it with other methods.

## Requirements

Ensure you have the following Python packages installed:

- `numpy`
- `scipy`
- `matplotlib`
- `networkx`
- `cvxpy` (for the IPG optimizer)
- `tensorflow` (for the ADAM optimizer)

You can install these packages using pip:

```bash
pip install numpy scipy matplotlib networkx cvxpy tensorflow

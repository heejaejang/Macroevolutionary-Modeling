# Macroevolutionary Modeling of Continuous Trait Evolution

## Overview

This project uses R to simulate and visualize continuous trait evolution under different evolutionary models. The analysis explores how evolutionary rate, phylogenetic history, and selection can influence patterns of phenotypic variation.

## Files

| File | Description |
|---|---|
| `Macroevolution_Modeling.Rmd` | Original analysis in R |
| `Macroevolutionary_Modeling.ipynb` | Python port (numpy / pandas / matplotlib) |


## Models and Analysis

### Brownian Motion

Brownian Motion (BM) simulations are used to examine how different evolutionary rate parameters affect the accumulation of trait variance through time.

The analysis includes:

* Individual evolutionary random walks
* Simulations of 76 independent lineages
* Comparison of high- and low-variance evolutionary regimes

### Phylogenetic Trait Evolution

Brownian Motion is projected onto simulated birth-death phylogenetic trees representing different evolutionary time scales.

Simulated body and tail lengths are visualized alongside empirical measurements from modern baleen whale genera.

### Ornstein-Uhlenbeck Models

Ornstein-Uhlenbeck (OU) simulations examine how selection toward an adaptive optimum influences trait evolution.

The analysis compares:

* Strong selective pull toward an optimum
* Weak selective pull toward an optimum

## Tools

* R
* R Markdown
* `phytools`
* `TreeSim`
* `tidyverse`
* `ggplot2`
* `diverge`

## Repository Contents

| File                             | Description                                                                 |
| -------------------------------- | --------------------------------------------------------------------------- |
| `Macroevolutionary_Modeling.Rmd` | Main R Markdown analysis containing simulations, models, and visualizations |
| `project_2.Rproj`                | RStudio project file                                                        |
| `svg/`                           | SVG figures and visual outputs                                              |

## Reference

Slater, G. J., Goldbogen, J. A., & Pyenson, N. D. (2017). Independent evolution of baleen whale gigantism linked to Plio-Pleistocene ocean dynamics. *Proceedings of the Royal Society B: Biological Sciences, 284*(1855), 20170546.

## Purpose

This project was developed to apply evolutionary modeling concepts and R-based data analysis to questions involving continuous trait evolution and phenotypic diversification.


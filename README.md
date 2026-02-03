# Pharmacokinetic Drug Concentration Model

## Overview
This project models drug concentration in the bloodstream over time using
a first-order elimination assumption. The goal is to analyze how dosage
and elimination rate affect drug concentration.

## Assumptions
- Single, well-mixed compartment
- Instantaneous drug absorption
- First-order elimination kinetics

## Tools Used
- Python
- NumPy
- Matplotlib

## Results
The model demonstrates exponential decay in drug concentration over time.
Increasing dosage increases peak concentration, while higher elimination
rates reduce drug persistence. Safety thresholds were also incorporated
to evaluate toxic risk.

## Limitations & Future Work
This model does not account for delayed absorption, multiple compartments,
or patient variability. Future work could extend this to multi-compartment
pharmacokinetic models.

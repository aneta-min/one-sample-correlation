# Comparing Correlations Between Cranial and Facial Measurements

## Overview

This project investigates whether the correlation between maximum cranial height (`skull_pH`) and morphological facial height (`face_H`) differs between male and female individuals.

The analysis uses the dataset `one-sample-correlation-skull-mf.txt` and compares the sex-specific correlation coefficients.

## Research Question

Does the correlation between maximum cranial height and morphological facial height among men differ from the corresponding correlation among women?

## Variables

| Variable | Description | Unit |
|---|---|---|
| `skull_pH` | Maximum cranial height | mm |
| `face_H` | Morphological facial height | mm |

## Statistical Methods

The analysis consists of the following steps:

1. Exploratory analysis of both variables in male and female samples.
2. Assessment of bivariate normality using Mardia’s test.
3. Comparison of the correlation coefficients between the two groups.
4. Hypothesis testing using:
   - the critical region;
   - a confidence interval in the Wald case;
   - p-values based on the specified test statistics.

## Data

The analysis uses the dataset:

`one-sample-correlation-skull-mf.txt`

The dataset should only be redistributed if its original source and license permit it.

## Tools

- R
- Quarto
- Statistical hypothesis testing
- Multivariate normality testing

## Reproducibility

The analysis can be reproduced using the original Quarto source file and the dataset.

## Author

Aneta Minibergerová  
Applied Mathematics, Masaryk University

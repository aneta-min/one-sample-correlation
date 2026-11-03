Comparing Correlations Between Cranial and Facial Measurements
Overview
This project investigates whether the correlation between maximum cranial height (skull_pH) and morphological facial height (face_H) differs between male and female individuals.

The analysis uses one-sample-correlation-skull-mf.txt and compares the sex-specific correlation coefficients.
Research question
Is the correlation between maximum cranial height and morphological facial height among men different from the corresponding correlation among women?
Variables
Variable	Description	Unit
skull_pH	Maximum cranial height	mm
face_H	Morphological facial height	mm
Sex	Grouping variable (male/female)	—


Statistical methodology
The analysis is planned in the following stages:
1. Exploratory analysis of both variables in the male and female samples.
2. Assessment of bivariate normality in each sample using Mardia’s test.
3. Comparison of the male and female correlation coefficients.
4. Reporting the hypothesis test using:
   - the critical region;
   - a confidence interval (Wald case only);
   - p-values based on the specified test statistics.
The significance level and exact test-statistic variants should be specified in the analysis document.
Data
Dataset: one-sample-correlation-skull-mf.txt

Please check the original data source and license before redistributing the dataset. If redistribution is not permitted, provide instructions for obtaining it instead of uploading the raw data.
Repository contents
- README.md — project overview and methodology.
- index.html — GitHub Pages landing page.
- one-sample-correlation-skull-mf.txt — dataset, if redistribution is permitted.
- Analysis source/output files — add the relevant .qmd, .R, or rendered HTML files.
Reproducibility
The analysis is intended to be reproducible in R. To reproduce the results, obtain the dataset, open the source analysis file, and run its code.

Add package requirements and execution instructions once they are finalized.
Author
Aneta Minibergerová
Applied Mathematics, Masaryk University

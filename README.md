Statistical Test Selection in R
Hypothesis Testing Using the Palmer Penguins Dataset

This repository contains a structured statistical analysis notebook demonstrating how different hypothesis tests are selected based on variable types and distributional assumptions.

The analysis is conducted in R and implemented in a Jupyter Notebook.

Main Notebook

selecting-the-appropriate-statistical-test.ipynb

The notebook walks through a series of predefined hypotheses using the Palmer Penguins dataset.

Analyses Included

1. Species vs Island

Crosstabulation

Pearson’s Chi-square test of independence

Interpretation of association

2. Culmen Length vs Culmen Depth

Descriptive statistics (mean, median, skewness, kurtosis)

Density plots

Shapiro–Wilk normality testing

Spearman rank correlation

Kendall tau correlation

3. Species vs Flipper Length

Group-wise normality testing

Kruskal–Wallis test

Dunn post-hoc test with Bonferroni correction

4. Sex vs Body Mass (within species)

Data cleaning

Normality testing within groups

Independent two-sample t-tests

Focus of the Project

This project demonstrates:

formulation of statistical hypotheses

selection of appropriate tests based on variable type

handling of non-normal distributions

use of non-parametric alternatives

interpretation of statistical output

The emphasis is on methodological reasoning and correct application of classical statistical tests.

Dataset

The analysis uses the Palmer Penguins dataset, which contains physical measurements of penguins from three islands in the Palmer Archipelago, Antarctica.

Raw data is not stored in this repository.

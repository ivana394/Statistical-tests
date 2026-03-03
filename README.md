# 📊 Statistical Test Selection in R

A structured hypothesis-testing notebook using the Palmer Penguins dataset.

This project demonstrates how statistical tests are selected based on:

- variable type  
- number of groups  
- distributional assumptions  

All analyses are implemented in **R** within a Jupyter Notebook.

---

## 📘 Main Notebook

`selecting-the-appropriate-statistical-test.ipynb`

The notebook walks through four predefined hypotheses and applies corresponding statistical tests.

---

## 🔍 Analyses Included

### 1️⃣ Species vs Island  
**Chi-square test of independence**

- Crosstabulation  
- Pearson’s Chi-square test  
- Interpretation of association  

---

### 2️⃣ Culmen Length vs Culmen Depth  
**Spearman & Kendall correlation**

- Descriptive statistics  
- Density plots  
- Shapiro–Wilk normality testing  
- Spearman rank correlation  
- Kendall tau correlation  

---

### 3️⃣ Species vs Flipper Length  
**Kruskal–Wallis test + Dunn post-hoc**

- Group-wise normality testing  
- Kruskal–Wallis test  
- Dunn test with Bonferroni correction  
- Interpretation of pairwise differences  

---

### 4️⃣ Sex vs Body Mass (within species)  
**Independent two-sample t-tests**

- Data cleaning  
- Normality testing within groups  
- Independent t-tests performed separately per species  
- Interpretation of mean differences  

---

## 🧠 Skills Demonstrated

- Hypothesis formulation  
- Assumption-aware statistical testing  
- Use of non-parametric alternatives  
- Clear interpretation of statistical results  
- Structured analytical workflow in R  

---

## 🐧 Dataset

The analysis uses the **Palmer Penguins** dataset  
(physical measurements of penguins across three Antarctic islands).

Raw data is not included in this repository.

---

## 🎯 Purpose

This notebook serves as a portfolio example of applied statistical reasoning and implementation of classical hypothesis testing methods in R.

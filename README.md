# Biostatistical Analysis of Ethanol Pharmacokinetics

This repository contains the final project from the professional retraining program «Biostatistics and Medical Data Analysis» of the [Bioinformatics Institute](https://bioinf.me/en).

Our study investigates ethanol pharmacokinetics using biostatistical modeling approaches. We assessed the influence of multiple covariates on key pharmacokinetic parameters by fitting linear regression models.

# Contributors

**Students**:

1) [Anna Vronskaia](https://github.com/annavronskaia) (*BIOCAD, St. Petersburg*)

Contribution: data preparation, individual dataset analysis, regression analysis.

2) [Alexey Gordeev](https://github.com/deigord) (*Almazov National Medical Research Centre, St. Petersburg*)

Contribution: data preparation, functional programming, regression analysis, allometric scaling, repository management.

3) [Ekaterina Danilina](https://github.com/kat-dani) (*Kurgan State University, Kurgan*)

Contribution: data preparation, regression analysis.

4) [Milana Sagitova](https://github.com/sagitowam) (*Sechenov University, Moscow*)

Contriobution: data preparation, regression analysis, allometric scaling.

5) [Sergey Tsaregorodtsev](https://github.com/svtsar) (*Russian University of Medicine, Moscow*)

Contribution: data preparation, exploratory analysis, preparing presentations, writing thesis statements.

**Supervisor**:

[Alexander Petrov](https://github.com/petrov-aleks) (*University of Potsdam, Potsdam*)

## Table of content

[Structure of repository]()

[Introduction]()

[Goal and objectives]()

[Data]()

[Study plan]()

[Results]()

[Software Requirements]()

[References]()

## Structure of repository

## Introduction

Alcohol consumption remains a major contributor to the global burden of disease: in 2021 it ranked among the leading causes worldwide, and it is causally linked to more than 200 diagnostic categories. Alcohol dependence affects about 3.7% of the world’s adult population, and the economic costs attributed to alcohol use have been estimated at 2.6% of global GDP [1]. These facts motivate quantitative analyses of variability in ethanol pharmacokinetics across studies and conditions.

Ethanol pharmacokinetics (PK) after typical doses can be described by a one-compartment model with concentration-dependent (capacity-limited) elimination. Over relevant concentration ranges, a pseudo-linear decline may be observed (approximate zero-order behavior), which can justify a simplified linear description for specific analyses [2].

In this project, we quantified ethanol pharmacokinetic endpoints from published human datasets. The analysis was conducted in two stages. First, we explored models aimed at maximizing the coefficient of determination ($R^2$). Second, we focused on a predefined set of factors of primary interest: body weight (using three alternative metrics), sex, and feeding status.

Additionally, we evaluated allometric scaling approaches using both classical power exponents and exponents proposed by Matsumoto to assess their applicability to ethanol pharmacokinetics.

## Goal and objectives

So, the **goal of a project** is characterize ethanol pharmacokinetics (PK) using noncompartmental analysis and biostatistical methods, quantify variability, assess covariate effects, and evaluate translational scaling between human and rat PK.

**Objectives**:

 - Describe each ethanol PK dataset (design, dosing, sampling, covariates), calculate and harmonize PK variables.

 - Visualize individual profiles: plot subject-level concentration–time curves within each dataset to assess variability and data quality.

 - Build an explanatory model: fit and validate regression models linking PK outcomes to covariates.

 - Replicate the workflow in animal data and compare/scale results (e.g., allometric translation)

## Data

Human ethanol pharmacokinetic data (8 datasets) [3–8] and rat data (2 datasets) [9, 10] were analyzed.

![](figures/data.png)

## Study plan

![](figures/study_plan.png)

## Results

## Software Requirements

## References
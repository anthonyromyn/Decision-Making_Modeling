# Statistical Modeling of Human Decision-Making

**Hierarchical Regression · Behavioral Data · fMRI · Structural Equation Modeling · R**

## Overview

This project investigates how neural activity and expected values influence human decision-making, using statistical models of behavioral and fMRI data collected across repeated experimental trials.

The analysis combines **generalized linear mixed-effects models (GLMMs), linear mixed-effects models (LMMs), and structural equation modeling (SEM)** to investigate relationships between decision-making, neural activity, and individual differences.

The work originated during my computational neuroscience research at the University of Toronto and includes R analysis code and an accompanying research manuscript.

## Statistical and Technical Highlights

- **Hierarchical modeling:** Used mixed-effects regression with participant- and run-level grouping structures to account for repeated observations.
- **Binary outcome modeling:** Applied logistic mixed-effects regression to trial-level decisions.
- **Interaction effects:** Investigated how relationships between expected value, neural activity, and decisions varied with individual differences.
- **Mediation and moderation:** Used structural equation modeling to examine candidate indirect pathways and conditional effects.
- **Statistical inference:** Used bootstrap-based inference for modeled indirect effects and visualized fitted relationships.

## Research Question

How do neural signals representing the expected value of outcomes for oneself and others relate to decisions, and how might these relationships depend on individual differences in neural responses?

The analysis examines candidate pathways involving the dorsolateral prefrontal cortex (dlPFC), nucleus accumbens (NAcc), and ventromedial prefrontal cortex (vmPFC).

The models investigate statistical associations and proposed mechanisms; they do not independently establish causal relationships.

## Repository Contents

- `analysis.R` — R code for mixed-effects regression, visualization, and structural equation modeling.
- `write_up.pdf` — Accompanying research manuscript and interpretation.

**Data availability:** The original research data are not included. Reproducing the analyses requires access to the underlying datasets and the necessary R package dependencies.

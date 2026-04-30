---
title: "Psychological Impact Prediction — LightGBM Healthcare Classifier"
excerpt: "LightGBM model predicting patient psychological risk levels from medical and behavioral indicators. Achieved AUC 0.87 on imbalanced healthcare data, with classification reports and confusion-matrix visualizations designed for clinical interpretability."
collection: portfolio
date: 2024-09-30
permalink: /portfolio/psychological-impact-prediction/
---

**Role:** Independent project · **Period:** Jun 2024 – Sep 2024

## Overview

Developed a machine learning model to predict patients' psychological risk levels from medical and behavioral indicators, with explicit attention to interpretability for healthcare stakeholders who need to act on the predictions.

## What I did

- **Built a LightGBM-based classifier** for psychological risk prediction, chosen specifically for its strong performance on imbalanced tabular health data and its native support for categorical features.
- **Achieved AUC of 0.87** on a held-out evaluation set — a meaningful threshold for screening-tier healthcare classification, where the model supports rather than replaces clinical judgment.
- **Visualized results** using classification reports and confusion matrices structured for healthcare-stakeholder interpretability, so clinicians could see where the model was confident, where it was uncertain, and what its failure modes looked like.
- **Contributed to ongoing research** into AI-assisted mental health diagnostics and decision-support systems.

## Why it matters

Healthcare ML lives or dies on interpretability and calibration, not raw accuracy. A model that hits AUC 0.87 but produces opaque scores is less useful than a slightly less accurate model whose confidence and errors are legible to a clinician. This project was scoped around that constraint from the start.

## Tech stack

Python · LightGBM · scikit-learn · classification reports · confusion matrices · imbalanced classification · healthcare ML

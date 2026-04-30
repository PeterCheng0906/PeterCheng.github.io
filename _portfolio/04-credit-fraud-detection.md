---
title: "Credit Fraud Detection — Class Imbalance at Scale"
excerpt: "Independent ML project tackling severe class imbalance (500 frauds in 200K+ records). Benchmarked Random Forest, SGDClassifier, and MLP with PCA, downsampling, and class reweighting to identify the best algorithm for production fraud detection."
collection: portfolio
date: 2025-06-30
permalink: /portfolio/credit-fraud-detection/
---

**Role:** Independent project · **Period:** Mar 2025 – Jun 2025

## Overview

A focused study on what severe class imbalance does to fraud-detection model performance, and which combinations of resampling, dimensionality reduction, and model choice actually work in practice. The dataset: 200K+ credit transaction records, of which only ~500 were fraudulent — a ratio that breaks naive classifiers in well-known ways.

## What I did

- **Diagnosed the imbalance problem** quantitatively, showing how default classifier outputs collapse onto the majority class without intervention and why standard accuracy is meaningless here.
- **Applied multiple imbalance strategies** in a controlled comparison: downsampling the majority class, class reweighting in the loss function, and PCA-based dimensionality reduction to surface signal that gets lost in high-dimensional fraud features.
- **Benchmarked Random Forest, SGDClassifier, and MLP models** on misclassification rate, false negatives (the costly error in fraud), and computational efficiency — because production fraud detection needs to be fast as well as accurate.
- **Identified the optimal algorithm** for large-scale fraud detection given the tradeoffs, with a clear writeup of why the winning combination beat the alternatives.

## Why it matters

Class imbalance is the single most common reason ML models fail in fraud, medical, and security domains. This project is a clean case study in how to address it methodically — not just "throw SMOTE at it" but actually compare strategies on the metrics that matter for the business problem.

## Tech stack

Python · scikit-learn · Random Forest · SGDClassifier · MLPClassifier · PCA · class reweighting · downsampling · cross-validation

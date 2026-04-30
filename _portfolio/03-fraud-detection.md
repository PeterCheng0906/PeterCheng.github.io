---
title: "Transaction Fraud Detection ML Pipeline"
excerpt: "Production-ready fraud detection pipeline on 800K+ Google Pay transactions. Reduced false positives by 8.7% and improved recall by 2.87% through feature engineering, careful model selection, and a tuned GBDT. Volunteer engagement with Google engineers."
collection: portfolio
date: 2024-02-28
permalink: /portfolio/fraud-detection/
---

**Role:** Volunteer Data Scientist — Google Engineering Team · **Period:** Winter 2023

## Overview

Engineered a production-grade fraud detection pipeline over 800K+ Google Pay transactions, working alongside Google engineers in a volunteer capacity. The deliverable was a tuned Gradient Boosting model with stable performance across train/test splits — ready for deployment to a real fraud-prevention workflow.

## What I did

- **Built the full pipeline:** outlier detection, categorical encoding, feature engineering, and dataset splitting strategies designed for the heavy class imbalance typical of fraud detection (frauds are <1% of transactions).
- **Trained and benchmarked Logistic Regression, GBDT, and MLP models** with cross-validation and systematic hyperparameter tuning, comparing how each handled the precision–recall tradeoff that defines fraud-prevention systems.
- **Reduced false positives by 8.7% and improved recall by 2.87%** in the final model versus baseline — meaningful in production because false positives directly translate to legitimate customers being blocked.
- **Delivered a production-ready GBDT model** with stable train/test performance, suitable for deployment without additional retraining.

## Why it matters

Fraud detection lives or dies on the precision–recall tradeoff. Pushing recall up without driving false positives through the roof is the whole game, and the 8.7% reduction in false positives at slightly higher recall is exactly the kind of asymmetric improvement that fraud teams care about — it means fewer angry customers and more caught fraud, simultaneously.

## Tech stack

Python · scikit-learn · Logistic Regression · Gradient Boosting (GBDT) · MLP · cross-validation · hyperparameter tuning · feature engineering

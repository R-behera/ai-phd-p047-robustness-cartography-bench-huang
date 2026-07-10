# Research Brief

## Project Name

Robustness Cartography Bench: Trustworthy ML for Huang-Aligned Research

## Motivation

This project targets the intersection of **Trustworthy ML, RL, generative AI, high-dimensional statistics** and PhD-level research readiness. The goal is to produce a publishable-style artifact with a clear claim, reproducible experiments, and an honest account of failures.

## Hypothesis

A focused system that combines domain-specific inductive bias with rigorous evaluation will outperform generic baselines on reliability, generalization, or interpretability for the advisor-aligned task.

## Core Research Question

Can adaptive evaluation reveal robustness, safety, privacy, or fairness failures missed by static benchmarks?

## Novel Contribution

1. Build a task definition and dataset split that reflects a real weakness in current models.
2. Add one measurable method or evaluation contribution tied to Furong Huang's research area.
3. Report both positive results and failure cases with enough detail for another researcher to reproduce or challenge the claim.

## Data Plan

HELM-style suites, WILDS/OOD datasets, safety prompts, fairness datasets, and targeted red-team cases.

Advisor-specific slice: **Trustworthy ML, RL, generative AI, high-dimensional statistics**.

## Baselines

standard evaluation, random perturbation, gradient/prompt attacks, calibration-only defenses, and data filtering.

## Main Method

Start with the strongest reproducible baseline, then add one explicit contribution: provenance tracking, uncertainty estimation, progress-state modeling, controllable ranking, graph constraints, adaptive stress testing, or domain-prior regularization depending on the final task.

## Evaluation Metrics

attack success, worst-group performance, calibration, leakage indicators, repair effectiveness, and reproducibility.

## Ablations

- Remove the domain-specific component.
- Remove uncertainty, verification, or interpretability module if present.
- Vary training data scale.
- Evaluate in-domain and out-of-domain splits.
- Run at least three seeds when stochastic training materially affects results.

## Failure Analysis

Maintain a failure bank with input, expected behavior, observed behavior, suspected cause, fix attempted, and whether the fix generalized.

## Five-Week Milestones

1. Literature map, exact task definition, dataset access, and baseline target.
2. Dataset pipeline, first baseline, metrics dashboard, and experiment registry.
3. Main method prototype and initial ablations.
4. Robustness, OOD, or counterfactual evaluation with failure taxonomy.
5. Final experiments, paper-style report, reproducibility package, and SOP-ready summary.

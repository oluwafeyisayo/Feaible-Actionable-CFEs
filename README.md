# Feasible-Actionable-CFEs

Improving The Practical Utility of Counterfactual Explanations For Machine Learning Models

This repository provides a model-agnostic framework for generating Counterfactual Explanations (CFEs) for Machine Learning (ML) models. CFEs offer transparency by showing minimal, actionable changes to input features that can alter a model’s prediction, helping users understand, trust, and act upon algorithmic decisions.

Our framework leverages causal mechanisms and multi-objective optimization (NSGA-III) to generate realistic, actionable, and causally consistent counterfactuals. It simultaneously optimizes validity, minimality, and causality (effort and plausibility), while introducing a novel recourse efficiency metric to identify cost-effective, high-impact interventions.

The implementation has been validated on multiple tabular datasets and demonstrates up to 38.8% improvement in providing feasible, practical changes compared to existing frameworks.

This codebase enables researchers and practitioners to generate trustworthy, interpretable, and actionable CFEs for any predictive model, bridging the gap between complex ML models and real-world decision-making.

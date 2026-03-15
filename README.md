# Anterior’s Approach to Fairness Evaluation of Automated Prior Authorization System

Sai P. Selvaraj, Khadija Mahmoud MD, and Anuj Iravane

## Abstract
Increasing staffing constraints and turnaround-time pressures in Prior authorization (PA) have led to increasing automation of decision systems to support PA review. 
Evaluating fairness in such systems poses unique challenges because legitimate clinical guidelines and medical necessity criteria often differ across demographic groups,
making parity in approval rates an inappropriate fairness metric. We propose a fairness evaluation framework for prior authorization models based on model error rates rather 
than approval outcomes. Using 7,166 human-reviewed cases spanning 27 medical necessity guidelines, we assessed consistency in sex, age, race/ethnicity, and socioeconomic status. 
Our evaluation combined error-rate comparisons, tolerance-band analysis with a predefined ±5 percentage-point margin, statistical power evaluation, and protocol-controlled 
logistic regression. Across most demographics, model error rates were consistent, and confidence intervals fell within the predefined tolerance band, indicating no 
meaningful performance differences. For race/ethnicity, point estimates remain small, but subgroup sample sizes were limited, resulting in wide confidence intervals and 
underpowered tests, with inconclusive evidence within the dataset we explored. These findings illustrate a rigorous and regulator-aligned approach to fairness evaluation in administrative healthcare AI systems.

This repository hosts a preprint of our paper.

The official archival version will appear on arXiv shortly.

Copyright © 2026 Authors. All rights reserved.

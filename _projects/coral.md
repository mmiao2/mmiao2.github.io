---
layout: page
title: "CORAL: Inference-Time Steering via Residual Activations"
description: >
  Extracting distributed correctness signals from frozen LLM residual streams
  for calibration-aware, transferable steering at inference time.
img: assets/img/projects/coral.png
importance: 1
category: Interpretability & Steering
---

CORAL introduces a mechanistic interpretability approach to inference-time steering that extracts distributed correctness signals from frozen LLM residual stream activations via auxiliary probes, improving both accuracy and calibration with cross-task generalization.

Key contributions:
- Regularized MLP probes trained on residual stream activations to predict correctness residuals
- Cross-task transfer: probes trained on one dataset generalize to unseen benchmarks
- ~10% accuracy improvement and ~50% ECE improvement on average across models
- SAE ablations demonstrate that the correctness signal is distributed, not localized to individual features

**Status**: Under review at ICML 2026 (4.33 avg rating, Likely Accept)

**Authors**: Miranda Muqing Miao, Young-Min Cho, Lyle Ungar

[arXiv](https://arxiv.org/abs/2602.06022){: .btn}

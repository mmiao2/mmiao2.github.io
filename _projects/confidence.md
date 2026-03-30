---
layout: page
title: "Closing the Confidence-Faithfulness Gap"
description: >
  Mechanistic analysis showing calibration and confidence signals are
  linearly encoded but orthogonal, with adaptive steering to align them.
img: assets/img/projects/confidence.png
importance: 2
category: Interpretability & Steering
---

This work provides a mechanistic interpretability analysis of verbalized confidence faithfulness, showing that calibration and confidence signals are linearly encoded but orthogonal across three models. We identify the "Reasoning Contamination Effect" and introduce a two-stage adaptive steering pipeline that substantially improves calibration alignment.

Key findings:
- Confidence and correctness are linearly encoded in residual stream activations but occupy orthogonal subspaces
- The "Reasoning Contamination Effect": chain-of-thought reasoning contaminates confidence representations
- Two-stage adaptive steering pipeline that bridges the confidence-faithfulness gap

**Status**: Under review at COLM 2026

**Authors**: Miranda Muqing Miao, Lyle Ungar

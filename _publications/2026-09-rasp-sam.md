---
title: "Residual-Aware Structured Pruning with Dual-Stream Alignment for Adapter-Tuned SAM"
collection: publications
category: conferences
permalink: /publication/2026-09-rasp-sam
authors: 'Xin Luo, Chunjiang Wang, S. Kevin Zhou<sup>†</sup>'
excerpt: 'A residual-aware structured pruning framework for adapter-tuned SAM that bridges foundation models and resource-constrained clinical segmentation.'
date: 2026-09-01
venue: 'MICCAI (CCF-B)'
paperurl: '/files/rasp-sam-miccai2026.pdf'
slidesurl: ''
bibtexurl: ''
citation: 'Xin Luo, Chunjiang Wang, S. Kevin Zhou<sup>†</sup>. (2026). "Residual-Aware Structured Pruning with Dual-Stream Alignment for Adapter-Tuned SAM." <i>MICCAI 2026</i>, CCF-B.'
---

RASP-SAM is a structured pruning framework for adapter-tuned Segment Anything Models in medical image segmentation. It defines dependency-safe pruning units under attention, FFN, adapter, and residual couplings; ranks units with Orthogonal Residual Scoring; and restores accuracy using two-stage Dual-Stream Compensation. With only 20K calibration images from SA-1B and SA-Med2D-20M, it reduces SAM-Med2D encoder compute from 65.15G to 15.62G MACs and parameters from 270.1M to 63.4M at 76% sparsity while maintaining near-lossless segmentation performance.

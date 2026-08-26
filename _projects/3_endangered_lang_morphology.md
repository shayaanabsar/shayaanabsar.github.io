---
layout: page
title: Morphological Inflection for Endangered Languages
description: A Byte-Level ByT5 framework incorporating cross-lingual transfer and lemma masking for low-resource morphological generation.
importance: 3
category: research
github: https://github.com/shayaanabsar/code-switched-pos-tagging
---

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center mb-4">
  <div class="project-tags">
    <span class="badge badge-pill badge-primary">PyTorch</span>
    <span class="badge badge-pill badge-info">ByT5 (Byte-Level)</span>
    <span class="badge badge-pill badge-secondary">Cross-Lingual Transfer</span>
    <span class="badge badge-pill badge-danger">Low-Resource NLP</span>
  </div>
  <a href="https://github.com/shayaanabsar/code-switched-pos-tagging" target="_blank" class="btn btn-sm z-depth-0 mt-2 mt-md-0" style="border: 1px solid var(--global-divider-color);">
    <i class="fa-brands fa-github"></i> View Repository
  </a>
</div>

This research introduces a novel byte-level framework for morphological inflection specifically targeted at endangered and highly under-resourced languages.

### Core Contributions

- **Byte-Level Architecture**: Leverages **ByT5** to bypass the subword tokenization bottleneck common to polysynthetic and agglutinative low-resource languages, operating directly on raw bytes to prevent out-of-vocabulary degradation.
- **Three-Phase Cross-Lingual Transfer**: Implements a progressive training regimen transferring morphological inductive biases from high-resource typologically related languages to low-resource targets (evaluating Spanish→Quechua, Finnish→Northern Sámi, and Turkish→Crimean Tatar).
- **Lemma Masking Hypothesis**: Proposes a theoretical and empirical formulation explaining why masked language modeling targets over lemma stems substantially improve generative accuracy in downstream inflection tasks.
- **Impact**: Contributes computational tools and methodologies designed to aid language documentation, revitalization, and digital preservation efforts.

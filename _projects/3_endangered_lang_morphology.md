---
layout: page
title: Morphological Inflection for Endangered Languages
description: A Byte-Level ByT5 framework incorporating cross-lingual transfer and lemma masking for low-resource morphological generation.
importance: 3
category: research
---

This research introduces a novel byte-level framework for morphological inflection specifically targeted at endangered and highly under-resourced languages.

### Core Contributions

* **Byte-Level Architecture**: Leverages **ByT5** to bypass the subword tokenization bottleneck common to polysynthetic and agglutinative low-resource languages, operating directly on raw bytes to prevent out-of-vocabulary degradation.
* **Three-Phase Cross-Lingual Transfer**: Implements a progressive training regimen transferring morphological inductive biases from high-resource typologically related languages to low-resource targets (evaluating Spanish→Quechua, Finnish→Northern Sámi, and Turkish→Crimean Tatar).
* **Lemma Masking Hypothesis**: Proposes a theoretical and empirical formulation explaining why masked language modeling targets over lemma stems substantially improve generative accuracy in downstream inflection tasks.
* **Impact**: Contributes computational tools and methodologies designed to aid language documentation, revitalization, and digital preservation efforts.

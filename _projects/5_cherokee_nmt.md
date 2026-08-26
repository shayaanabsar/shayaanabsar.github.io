---
layout: page
title: Neural Machine Translation for Low-Resource Languages
description: Sequence-to-sequence transformer with custom attention mechanisms and beam search decoding for English–Cherokee translation.
importance: 5
category: research
github: https://github.com/shayaanabsar/ch-en-nmt
---

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center mb-4">
  <div class="project-tags">
    <span class="badge badge-pill badge-primary">PyTorch</span>
    <span class="badge badge-pill badge-info">Seq2Seq</span>
    <span class="badge badge-pill badge-success">Beam Search</span>
    <span class="badge badge-pill badge-secondary">Cherokee NLP</span>
  </div>
  <a href="https://github.com/shayaanabsar/ch-en-nmt" target="_blank" class="btn btn-sm z-depth-0 mt-2 mt-md-0" style="border: 1px solid var(--global-divider-color);">
    <i class="fa-brands fa-github"></i> View Repository
  </a>
</div>

A sequence-to-sequence neural machine translation system optimized for extreme low-resource language pairs, focusing on English to Cherokee translation.

### Highlights

- **Model Architecture**: Encoder-decoder transformer with customized cross-attention mechanisms tuned to prevent overfitting on limited parallel corpora.
- **Inference & Decoding**: Implemented beam search decoding with length penalty normalization to optimize translation hypothesis selection.
- **Data Processing & Tokenization**: Designed specialized tokenization and vocabulary construction pipelines handling character- and morpheme-level representations tailored to indigenous American language morphology.

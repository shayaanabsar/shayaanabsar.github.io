---
layout: page
title: PyTorch GPT from Scratch
description: Complete implementation of a decoder-only transformer architecture in PyTorch with custom multi-head attention and training pipeline.
importance: 4
category: engineering
---

An educational yet robust from-scratch implementation of an autoregressive Transformer (GPT) in pure PyTorch, designed to dissect the internal mechanics of foundation models.

### Key Components

* **Architecture**: Implemented multi-head causal self-attention, scaled dot-product attention, learnable positional embeddings, layer normalization (Pre-LN), and feed-forward projection sublayers from mathematical primitives.
* **Optimization & Training Pipeline**: Configured training routines featuring gradient accumulation, cosine annealing learning rate schedules with warm-up, weight decay filtering (excluding biases and 1D normalization tensors), and mixed-precision execution.
* **Text Generation**: Includes greedy decoding and top-$k$ / nucleus ($p$) sampling strategies with temperature control.

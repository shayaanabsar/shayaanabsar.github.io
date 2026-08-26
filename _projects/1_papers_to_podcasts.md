---
layout: page
title: Papers-to-Podcasts
description: Multi-stage pipeline converting complex academic papers into conversational audio using LLM orchestration, semantic search, and neural TTS.
importance: 1
category: engineering
github: https://github.com/shayaanabsar/papers-to-podcasts
---

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center mb-4">
  <div class="project-tags">
    <span class="badge badge-pill badge-primary">Python</span>
    <span class="badge badge-pill badge-info">LLM Orchestration</span>
    <span class="badge badge-pill badge-secondary">FAISS</span>
    <span class="badge badge-pill badge-success">Neural TTS</span>
    <span class="badge badge-pill badge-warning">Streamlit</span>
  </div>
  <a href="https://github.com/shayaanabsar/papers-to-podcasts" target="_blank" class="btn btn-sm z-depth-0 mt-2 mt-md-0" style="border: 1px solid var(--global-divider-color);">
    <i class="fa-brands fa-github"></i> View Repository
  </a>
</div>

**Papers-to-Podcasts** is an end-to-end pipeline that ingests academic papers (PDFs) and synthesizes engaging, multi-speaker conversational audio summaries.

### Architecture & Key Features

- **Document Ingestion & Chunking**: Parses structured scientific PDFs (10–30 pages) and indexes text sections into a high-dimensional vector space using **FAISS** for rapid semantic retrieval.
- **LLM Orchestration**: Coordinates prompts and role-playing agents to generate engaging dialogue between hosts, explaining technical concepts, methodology, and results in accessible language.
- **Neural Text-to-Speech**: Integrates state-of-the-art neural TTS models to produce natural multi-speaker audio with realistic pacing and intonation.
- **Deployment & Performance**: Fully deployed on **Streamlit Cloud** with optimized caching, capable of converting complete research papers into podcast episodes in under five minutes.

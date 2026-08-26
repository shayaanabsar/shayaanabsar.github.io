---
layout: page
title: Papers-to-Podcasts
description: Multi-stage pipeline converting complex academic papers into conversational audio using LLM orchestration, semantic search, and neural TTS.
importance: 1
category: engineering
---

**Papers-to-Podcasts** is an end-to-end pipeline that ingests academic papers (PDFs) and synthesizes engaging, multi-speaker conversational audio summaries.

### Architecture & Key Features

- **Document Ingestion & Chunking**: Parses structured scientific PDFs (10–30 pages) and indexes text sections into a high-dimensional vector space using **FAISS** for rapid semantic retrieval.
- **LLM Orchestration**: Coordinates prompts and role-playing agents to generate engaging dialogue between hosts, explaining technical concepts, methodology, and results in accessible language.
- **Neural Text-to-Speech**: Integrates state-of-the-art neural TTS models to produce natural multi-speaker audio with realistic pacing and intonation.
- **Deployment & Performance**: Fully deployed on **Streamlit Cloud** with optimized caching, capable of converting complete research papers into podcast episodes in under five minutes.

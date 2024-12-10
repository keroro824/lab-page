---
title: "InfiniAI Lab - Research"
layout: textlay
excerpt: "InfiniAI Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Research umbrella: Following directions all aim to strengthen the ability of “copilot”.
Key words: efficient inference, hardware-aware, long context modeling, sparsity, quantization, speculative decoding, semi-parametric  

## Co-design LLM algorithms with hardware properties
Design smarter algorithms that leverage hardware characteristics, e.g., model sparsity, flops and bandwidth ratio, memory hierarchy, cpu and gpu …
Enable impossible training/serving environment ,e.g., offloading, on-device, decentralized training, leveraging model characteristics, e.g., reparameterization, gradient, model structure, user query pattern … 

Example recent work:

[1] Sequoia: Scalable, Robust, and Hardware-aware Speculative Decoding. 2024 

[2] S2FT: Efficient, Scalable and Generalizable LLM Fine-tuning by Structured Sparsity. 2024

[3] HexGen: Generative Inference of Large-Scale Foundation Model over Heterogeneous Decentralized Environment

[4] Prompt-prompted Mixture of Experts for Efficient LLM Generation. 2024

[5] GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection. 2024

[6] Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time. 2023

[7] FlexGen: High-Throughput Generative Inference of Large Language Models with a Single GPU. 2023

[8] Fine-tuning Language Models over Slow Networks using Activation Compression with Guarantees. 2023

## Long-context modeling and generation
Enable functionality of long-context modeling, e.g., efficiency in fine tuning and serving, extrapolation ability, no context left behind
Enhance advanced long context understanding and instructability, e.g., retention and retrieval of information over long periods, ability to maintain continuity and coherence in long conversations

Example recent work:

[1] TriForce: Lossless Acceleration of Long Sequence Generation with Hierarchical Speculative Decoding. 2024

[2] Megalodon: Efficient LLM Pretraining and Inference with Unlimited Context Length. 2024

[3] Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding. 2024

[4] Get More with LESS: Synthesizing Recurrence with KV Cache Compression for Efficient LLM Inference. 2024

[5] KIVI: A Tuning-Free Asymmetric 2bit Quantization for KV Cache. 2024

[6] Efficient Streaming Language Models with Attention Sinks. 2023

[7] H2O: Heavy-Hitter Oracle for Efficient Generative Inference of Large Language Models. 2023


## Semi-parametric modeling for new scaling law
Enable new scaling law of model pretraining, e.g.,  model-led learning, learn to curate data, learn to use external memory, optimize parameter utilization, adapt to hardware
New paradigm of LLM serving, e.g., plugin contextual - persistent memory for tasks …

Example recent work:

[1] Memory Mosaics: Semi-parametric LLMs. 2024

[2] Learn To be Efficient: Build Structured Sparsity in Large Language Models. 2024

[3] HALOS: Hashing Large Output Space for Cheap Inference. 2022

[4] MONGOOSE: A Learnable LSH Framework for Efficient Neural Network Training. 2021

[5] SLIDE: In Defense of Smart Algorithms over Hardware Acceleration for Large-Scale Deep Learning Systems. 2020

## Enhancing Model’s Lookahead Planning and Reasoning Abilities 
Design new tasks and weakly supervised data collection algorithms for enhancing LLM abilities, e.g., RL, synthetic data, simulated world environment … 
Design new model architecture to extract planning and reasoning abilities, e.g., hierarchical / multiscale architecture, encoding abilities, looking ahead / backtracking…
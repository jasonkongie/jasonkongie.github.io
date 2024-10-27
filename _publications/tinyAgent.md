---
title: "Tiny Agent"
collection: publications
permalink: /publication/tinyagent
excerpt: 'TinyAgent: Quantization-aware Model Compression and Adaptation for On-device LLM Agent Deployment'
authors: Jason Kong, Lanxiang Hu, Flavio Ponzina, Tajana Rosing 
date: 2024-07-26
venue: 'ICML'
---

**Abstract:** Deploying LLMs on edge devices is challenging due to stringent memory resources and compute constraints. In edge applications, existing deployment solutions for LLM agents disaggregate the fine-tuning process for domain-specific adaptation and the post-training model compression process. As a result, it requires extensive experimentation to find a readily available model compression technique that minimizes a fine-tuned model's performance loss while satisfying a target hardware's memory constraints. To address this problem, we propose TinyAgent, which optimizes the deployment workflow by using a quantization-aware model compression technique for specialized decision-making LLM agents under resource-constrained environments. Our approach takes into account both deployment-time hardware constraints and challenges in post-training quantization during fine-tuning. Experimental results demonstrate that our approach not only achieves 8x less memory usage to make LLM inference possible across a variety of edge devices, but also consistently speeds up LLM inference by up to without compromising accuracy.
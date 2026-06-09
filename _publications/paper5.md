---
title: "Evaluating LoRA Placement Strategies across Large Language Models: A Multi-Dimensional Efficiency Framework"
collection: publications
category: llm
permalink: /publication/paper5
status: in_preparation
excerpt: 'Studies how LoRA placement across Transformer modules affects model performance, training efficiency, and memory usage, aiming to identify resource-aware fine-tuning strategies for large language models.'
date: 2025-06-01
venue: 'Manuscript in preparation'
paperurl: ''
---

**Abstract:** Low-Rank Adaptation (LoRA) provides an efficient approach for fine-tuning large language models by updating a small number of trainable parameters. However, the choice of where to insert LoRA modules can significantly affect model quality, training efficiency, and memory usage. This work presents a multi-dimensional evaluation of LoRA placement strategies across Transformer components, including attention and feed-forward modules. By jointly analyzing downstream performance, training throughput, and memory consumption, the study investigates how different insertion choices lead to distinct accuracy-efficiency trade-offs. The goal is to provide practical guidance for resource-aware fine-tuning of large language models under different computational constraints.
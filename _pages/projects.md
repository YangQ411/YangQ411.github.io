---
title: "Projects"
permalink: /projects/
author_profile: true 
---

Here are selected research projects related to large language models, reinforcement learning, reasoning, and AI for scientific discovery.

---

## Featured Research Projects

<div class="project-card">
  <img src="/images/projects/Reatrace.png" alt="ReaTrace Project" class="project-img">

  <div class="project-content">

### ReaTrace: Reasoning Trajectory Analysis for Large Language Models

ReaTrace studies LLM reasoning as a structured state-transition trajectory rather than only evaluating final-answer correctness. The project aims to develop process-level metrics for analyzing how information, constraints, uncertainty, and unresolved problem structure evolve across intermediate reasoning steps.

**Keywords:** LLM reasoning, reasoning trajectory, process-level evaluation, uncertainty reduction, constraint accumulation

[GitHub Repo](https://github.com/YangQ411/ReaTrace-Reasoning-Trajectory-Analyzer)

  </div>
</div>

---

<div class="project-card">
  <img src="/images/projects/StringCosmo.png" alt="AI for Scientific Discovery Project" class="project-img">

  <div class="project-content">

### AI-Assisted Scientific Discovery in Gravitational and Cosmological Models

This project explores whether AI-guided systems can assist in discovering analytical structures under mathematical and physical constraints. It combines candidate generation, symbolic verification, and physical filtering to search for valid solution forms in theoretical physics and cosmology.

**Keywords:** AI for Science, theoretical physics, symbolic reasoning, analytical structure discovery, verification-guided search

[GitHub Repo](https://github.com/YangQ411/StringCosmoAI)

  </div>
</div>

---

## Selected LLM Projects

<div class="project-card">
  <img src="/images/projects/lora_parallel_llama.png" alt="LoRA and Distributed Training Project" class="project-img">

  <div class="project-content">

### Efficient Fine-Tuning and Distributed Optimization for Large Language Models

Explored LoRA fine-tuning, mixed-precision training, and distributed optimization strategies for LLaMA 3.2-1B. This project evaluates trade-offs among model performance, training throughput, and memory usage under practical computational constraints.

**Keywords:** LoRA, PEFT, mixed precision, DDP, FSDP, efficient LLMs

[GitHub Repo](https://github.com/YangQ411/Hybrid-Fine-Tuning-and-Parallelism-Training-for-Llama3-)

  </div>
</div>

---

<div class="project-card">
  <img src="/images/projects/dpo_scratch.png" alt="DPO from Scratch Project" class="project-img">

  <div class="project-content">

### From-Scratch Direct Preference Optimization

Reimplemented Direct Preference Optimization from scratch to better understand the mathematical formulation and training behavior of preference-based language model optimization. This project serves as a foundation for studying RLHF, preference learning, and RL-based LLM alignment.

**Keywords:** DPO, preference optimization, RLHF, alignment, policy optimization

[GitHub Repo](https://github.com/YangQ411/dpo-scratch.git)

  </div>
</div>

---

<div class="project-card">
  <img src="/images/projects/LiverMore.png" alt="Livermore RLHF Project" class="project-img">

  <div class="project-content">

### Personalized Chatbot with RLHF

Built a domain-specific RLHF pipeline for a personalized chatbot, including supervised fine-tuning, preference optimization, evaluation, and an interactive Gradio interface. The project explores how preference-based training can align a language model toward a specific reasoning style and decision logic.

**Keywords:** RLHF, DPO, SFT, persona alignment, LLaMA, Gradio

[GitHub Repo](https://github.com/YangQ411/Livermore-RLHF.git)

  </div>
</div>

---

## Other Projects

### LLM Evaluation Framework

Developed a customized evaluation framework combining standard metrics and LLM-as-a-judge evaluation for instruction-following and multi-turn dialogue assessment.

**Keywords:** LLM evaluation, MT-Bench, LLM-as-a-judge, instruction following

[GitHub Repo](https://github.com/YangQ411/LLM-Eval-Pipeline)

---

## Previous Physics Research

### Non-singular String Cosmology with Matter Sources via All-order α′ Corrections

Studied non-singular cosmological solutions in string theory with matter sources and all-order α′ corrections.

### Quasi-topological Gravity from String Theory in Cosmological Background

Explored quasi-topological gravity structures motivated by string theory and their cosmological implications.


<style>
.project-card {
  display: flex;
  gap: 24px;
  align-items: flex-start;
  margin: 28px 0 34px 0;
}

.project-img {
  width: 220px;
  max-width: 220px;
  border-radius: 8px;
  border: 1px solid #e5e5e5;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
}

.project-content {
  flex: 1;
}

.project-content h3 {
  margin-top: 0;
  margin-bottom: 10px;
}

.project-content p {
  margin-bottom: 10px;
}

@media (max-width: 768px) {
  .project-card {
    flex-direction: column;
  }

  .project-img {
    width: 100%;
    max-width: 100%;
  }
}
</style>


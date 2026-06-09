---
title: "Projects"
permalink: /projects/
author_profile: true 
---

Here are selected research projects related to large language models, reinforcement learning, reasoning, and AI for scientific discovery.

---

<div class="project-card">
  <div class="project-image">
    <img src="/images/projects/Reatrace.png" alt="ReaTrace Project">
  </div>

  <div class="project-info">
    <h3>ReaTrace: Reasoning Trajectory Analysis for Large Language Models</h3>

    <p>
      ReaTrace explores process-level analysis of LLM reasoning beyond final-answer accuracy. The project focuses on understanding how reasoning unfolds across intermediate steps and how different reasoning trajectories can be compared in mathematical problem-solving tasks.
    </p>

    <p>
      <a href="https://github.com/YangQ411/ReaTrace-Reasoning-Trajectory-Analyzer">GitHub Repo</a>
    </p>
  </div>
</div>

<div class="project-card">
  <div class="project-image">
    <img src="/images/projects/StringCosmo.png" alt="AI for Scientific Discovery Project">
  </div>

  <div class="project-info">
    <h3>AI-Assisted Scientific Discovery in Gravitational and Cosmological Models</h3>

    <p>
      This project explores whether AI-guided systems can assist in discovering analytical structures under mathematical and physical constraints. It combines candidate generation, symbolic verification, and physical filtering to search for valid solution forms in theoretical physics and cosmology.
    </p>

    <p>
      <a href="https://github.com/YangQ411/StringCosmoAI">GitHub Repo</a>
    </p>
  </div>
</div>

<div class="project-card">
  <div class="project-image">
    <img src="/images/projects/lora_parallel_llama.png" alt="LoRA and Distributed Training Project">
  </div>

  <div class="project-info">
    <h3>Efficient Fine-Tuning and Distributed Optimization for Large Language Models</h3>

    <p>
      Explored LoRA fine-tuning, mixed-precision training, and distributed optimization strategies for LLaMA 3.2-1B. This project evaluates trade-offs among model performance, training throughput, and memory usage under practical computational constraints.
    </p>

    <p>
      <a href="https://github.com/YangQ411/Hybrid-Fine-Tuning-and-Parallelism-Training-for-Llama3-">GitHub Repo</a>
    </p>
  </div>
</div>

<div class="project-card">
  <div class="project-image">
    <img src="/images/projects/dpo_scratch.png" alt="DPO from Scratch Project">
  </div>

  <div class="project-info">
    <h3>From-Scratch Direct Preference Optimization</h3>

    <p>
      Reimplemented Direct Preference Optimization from scratch to better understand the mathematical formulation and training behavior of preference-based language model optimization. This project serves as a foundation for studying RLHF, preference learning, and RL-based LLM alignment.
    </p>

    <p>
      <a href="https://github.com/YangQ411/dpo-scratch.git">GitHub Repo</a>
    </p>
  </div>
</div>

<div class="project-card">
  <div class="project-image">
    <img src="/images/projects/LiverMore.png" alt="Livermore RLHF Project">
  </div>

  <div class="project-info">
    <h3>Personalized Chatbot with RLHF</h3>

    <p>
      Built a domain-specific RLHF pipeline for a personalized chatbot, including supervised fine-tuning, preference optimization, evaluation, and an interactive Gradio interface. The project explores how preference-based training can align a language model toward a specific reasoning style and decision logic.
    </p>

    <p>
      <a href="https://github.com/YangQ411/Livermore-RLHF.git">GitHub Repo</a>
    </p>
  </div>
</div>

---

## Other Projects

### LLM Evaluation Framework

Studied evaluation methods for instruction-following LLMs, including lexical metrics, perplexity-based analysis, and LLM-as-a-judge evaluation. The project explores how different evaluation signals capture response quality in open-ended and multi-turn dialogue tasks.

[GitHub Repo](https://github.com/YangQ411/LLM-Eval-Pipeline)

---

<style>
.project-card {
  display: flex;
  gap: 24px;
  align-items: flex-start;
  margin: 32px 0;
  padding-bottom: 28px;
  border-bottom: 1px solid #eaeaea;
}

.project-image {
  flex: 0 0 230px;
}

.project-image img {
  width: 230px;
  max-width: 230px;
  border-radius: 6px;
  border: 1px solid #e5e5e5;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
}

.project-info {
  flex: 1;
}

.project-info h3 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.05em;
}

.project-info p {
  margin-bottom: 10px;
  line-height: 1.55;
}

@media (max-width: 768px) {
  .project-card {
    flex-direction: column;
  }

  .project-image {
    flex: none;
    width: 100%;
  }

  .project-image img {
    width: 100%;
    max-width: 100%;
  }
}
</style>


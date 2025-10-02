---
title: "Projects"
permalink: /projects/
author_profile: true 
---

Here are some of my selected projects:

## Large Language Models (LLMs)

## Explored efficient fine-tuning and distributed optimization strategies for Large Language Models    
- Selected Llama 3.2-1B and applied **LoRA** to attention layers on the OpenOrca dataset. 
- Implemented and evaluated mixed-precision training (**FP32, FP16, BF16**), achieving ~**5×** throughput improvement and ~**20%** GPU memory savings.
- Compared parallel training methods (**DDP vs. FSDP**), identifying efficiency–scalability trade-offs across cluster sizes.
- Accelerated preprocessing with Dask + SLURM, reducing tokenization time by over **50%**.
- Deployed a Gradio chatbot demo to showcase fine-tuned model interaction.

[GitHub Repo](https://github.com/YangQ411/Hybrid-Fine-Tuning-and-Parallelism-Training-for-Llama3-)

---

## Personalized Chatbot with RLHF
- Designing a domain-specific chatbox capable of emulating the style of a renowned economist to address targeted economic questions.  
- Leveraging a pretrained LLaMA-3 model as the base system and extending it with reinforcement learning methods (PPO/DPO) for alignment.  
- Planning to integrate preference-based reward modeling to refine responses toward domain-specific quality and consistency.  
- Expected outcome: demonstrate the effectiveness of RLHF/DPO for style emulation and domain adaptation, highlighting practical applications of aligned LLMs.

[GitHub Repo](https://github.com/YangQ411/llama-lora-study)

---

## LLM Evaluation Framework: Custom Benchmark and MT-Bench with LLM-as-a-Judge
- Developed a customized evaluation pipeline by fine-tuning Llama-3 with LoRA on OpenOrca.  
- Compared standard metrics (BLEU, ROUGE, Perplexity) with LLM-as-a-judge approaches using GPT-4. 
- Created **InstructEval-200** (7 categories) and integrated MT-Bench for multi-turn dialogue evaluation  
- Results showed +17% accuracy improvement on InstructEval-200 and **+10%** on MT-Bench, with particularly strong gains in STEM (**+40%**) and Humanities (**+27.5%**).
- Findings across both benchmarks were consistent, reinforcing the validity of LLM-as-a-judge for instruction-following evaluation.
- The framework and results are open-sourced, making the study reproducible for the community.

[GitHub Repo](https://github.com/YangQ411/LLM-Eval-Pipeline)

---

## Physics Research (Past Work)

## Non-singular String Cosmology with Matter Sources via All-order α′ Corrections
- Investigated the cosmological singularity problem in string theory with matter sources. 
- Derived O(d,d)-covariant equations of motion including all-order α′ corrections, generalizing known vacuum results. 
- Constructed perturbative and non-perturbative solutions, showing smooth evolution without singularities. 
- Discussed implications of higher-derivative string corrections for early-universe cosmological models.
- Manuscript in preparation — available upon request.

---

## Derive Quasi-topological Gravity from String Theory in Cosmological Background
- Conducted a literature review of quasi-topological gravity and its relation to Lovelock’s theory of gravity from string theory.  
- Calculated curvature tensors using a self-developed Python program and validated calculations against theoretical models. 
- Derived quasi-topological gravity from string theory in the cosmological background.
- Drafted preliminary manuscript, highlighting potential connections between higher-order gravity corrections and cosmology.  

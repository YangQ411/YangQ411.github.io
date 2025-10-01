---
title: "Projects"
permalink: /projects/
author_profile: true 
---

Here are some of my selected projects:

## Large Language Models (LLMs)

## Explored efficient fine-tuning and distributed optimization strategies for Large Language Models:
- Selected Llama 3.2-1B and applied LoRA to attention layers on the OpenOrca dataset. 
- Implemented and evaluated mixed-precision training (FP32, FP16, BF16), achieving ~5× throughput improvement and ~20% GPU memory savings.
- Compared parallel training methods (DDP vs. FSDP), identifying efficiency–scalability trade-offs across cluster sizes.
- Accelerated preprocessing with Dask + SLURM, reducing tokenization time by over 50%.
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

## Survey and Benchmarking of LLM Evaluation Methods
- Fine-tuned a Llama-3 model with LoRA on the OpenOrca dataset to develop a customized instruction-tuned model for evaluation experiments.  
- Analyzed model outputs along QA accuracy and instruction-following dimensions via token-level generation analysis.  
- Implemented LLM-based automatic evaluation using GPT-4 as the judge, assessing the fine-tuned model on MT-Bench and a custom dataset to measure performance reliably.  
- Compared traditional metrics (BLEU, ROUGE, Perplexity) with LLM-based judgments, identifying the key advantages and limitations of each paradigm to guide more robust evaluation strategies.

[GitHub Repo](https://github.com/YangQ411/LLM-Eval-Pipeline)

---

## Physics Research (Past Work)

## Non-singular String Cosmology with Matter Sources via all Order alpha prime  Corrections
- Conducted background research on classical singularities in cosmology. 
- Studied string-theoretic corrections in non-singular cosmology via alpha prime expansion and derived kinematic equations describing cosmic evolution. 
- Solved equations using Wolfram Mathematica and visualized solution trends for matter-driven cosmological models. 

[Paper Draft](#)

---

## Derive Quasi-topological Gravity from String Theory in Cosmological Background
- Made a literature review of quasi-topological gravity and the process of deriving Lovelock’s theory of gravity from string theory.  
- Calculated the curvature tensor using a self-designed program with python.  
- Derived quasi-topological gravity from string theory in the cosmological background.  

[Paper Draft](#)
---
title: "LSC-DPO: Learning-Signal-Controlled Direct Preference Optimization"
collection: publications
category: llm
permalink: /publication/paper4
status: submitted
excerpt: 'Proposes a learning-signal-controlled variant of Direct Preference Optimization that dynamically regulates the preference margin signal to improve training stability and alignment performance.'
date: 2025-06-01
venue: 'Submitted'
paperurl: ''
---

**Abstract:** Direct Preference Optimization (DPO) has become a standard reward-model-free approach for aligning language models with preference data. However, as DPO optimization progresses, the logistic preference loss can become less responsive to further changes, so gradients become smaller and preference updates induce only limited changes to the policy. In this paper, we study DPO from a training-dynamics perspective and identify the sigmoid gradient factor as a learning signal that determines the strength of preference updates. This signal depends on the DPO coefficient $\beta$, which motivates using $\beta$ as a control variable for regulating DPO training dynamics. We propose Learning-Signal-Controlled Direct Preference Optimization (LSC-DPO), a multiplicative coefficient-control rule that keeps the learning signal close to a target level while preserving the original DPO objective. A log-space analysis further establishes when the proposed control update remains stable and tracks the target learning-signal level. Experiments with Llama3-8B and Qwen3-8B on AlpacaEval~2 and MT-Bench, together with controlled studies on Anthropic-HH, show that LSC-DPO improves over DPO and strong preference-optimization baselines on the main alignment metrics. On AlpacaEval~2, LSC-DPO improves length-controlled win rate over DPO by 3.5 points on Llama3-8B and 4.9 points on Qwen3-8B. Training-dynamics analyses further show that LSC-DPO maintains more sustained and stable learning-signal dynamics throughout preference optimization.


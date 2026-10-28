---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

_Last updated: October 2026_

**Seeking:** LLM post-training research internship (reinforcement learning / coding agents / general agents) in Beijing, available from early December 2026 for 3+ months.

**Education**

* **M.Eng. in Electronic Information (Computer Science and Technology), Tsinghua University, Expected June 2028**  
  
  * Advisor: Associate Professor [Jianfei Chen](https://ml.cs.tsinghua.edu.cn/~jianfei/)
  * Research group: [TSAIL](https://ml.cs.tsinghua.edu.cn/), led by Professor [Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml)

* **B.Eng. in Computer Science and Technology, Tsinghua University, June 2026**  
  
  * Major GPA: 3.8/4.0
  * Relevant coursework (grade A or above): Ordinary Differential Equations; Probability and Statistics; Fundamentals of Programming; Programming and Training; Software Engineering; Operating Systems; Principles of Signal Processing; Database Special Topic Training
  * Previous major: Medicine. Transitioned to Computer Science to pursue a passion for artificial intelligence.

**Research Statement**

  * My research focuses on post-training of large models (reinforcement learning and data synthesis) and on agents, with the goal of improving capabilities on long-horizon tasks such as long-context reasoning, long-form generation, and complex coding. I also transfer effective reinforcement learning techniques from LLMs to diffusion and video generation models.

**Publications**

* **LongZero: Enhancing Long-Context Reasoning in LLMs from Zero Data**  
  **Zhennan Wan**, Jianfei Chen  
  Under review at ACL Rolling Review, October 2026. [[arXiv](https://arxiv.org/abs/2610.30132)] [[Code](https://github.com/zhennan1/LongZero)]

* **Scaling Long-Form Story Generation via Narrative State Tracking**  
  **Zhennan Wan**, Jianfei Chen  
  Under review at ICLR 2027. [[arXiv](https://arxiv.org/abs/2609.35759)] [[Code](https://github.com/zhennan1/NstAgent)]

* **Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration**  
  Zijun Liu\*, **Zhennan Wan\***, Peng Li, Ming Yan, Fei Huang, Yang Liu (\*equal contribution)  
  ACL 2026 Main Conference. [[Paper](https://aclanthology.org/2026.acl-long.468/)] [[Code](https://github.com/THUNLP-MT/ExtAgents)] [[Data](https://huggingface.co/datasets/zhennan1/ExtAgents)]

**Research Experience**

* **September 2025 - Present: Research Member, Tsinghua Statistical Artificial Intelligence and Learning Group (TSAIL), Tsinghua University**
  * **Reinforcement Learning for Diffusion Models** (ongoing)
    * Transferring techniques proven effective in LLM reinforcement learning to diffusion models.
    * Systematically comparing step-wise likelihood methods (Flow-GRPO) with regression-based methods (DiffusionNFT, AWM) to design RL algorithms that are more efficient, more stable, and more robust to reward overfitting.
  * **LongZero: Enhancing Long-Context Reasoning in LLMs from Zero Data** (first author, under review)
    * Extended zero-data reinforcement learning from short-context to long-context tasks: the model constructs its own multi-hop reasoning and multi-round retrieval tasks, expands them into long-context data, and trains itself with GRPO.
    * The method generalizes to general long-context reasoning, outperforming RL baselines trained on data synthesized from external corpora across 2 models and 5 benchmarks.
  * **Scaling Long-Form Story Generation via Narrative State Tracking** (first author, under review)
    * Studied length scaling in long-form fiction generation and designed an evaluation method for narrative consistency.
    * Proposed NstAgent, an agent framework in which the model explicitly tracks structured narrative states, scaling story generation from 10,000 to 100,000 words without noticeable loss in consistency or writing quality.
    * With reinforcement learning, a 4B model matched its 9B counterpart from the same model family.

* **September 2024 - May 2025: Research Intern, Natural Language Processing and Social Humanities Computing Lab (THUNLP), Tsinghua University**
  * **Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration**
    * Developed ExtAgents, a multi-agent framework that distributes external knowledge across agents and enables intensive inter-agent communication, scaling external knowledge input beyond the context window without long-context training.
    * Built the multi-hop QA benchmark ∞Bench+; on it and on tasks such as long survey generation, ExtAgents significantly outperformed existing training-free methods at the same input size, with performance improving as more knowledge is provided.

* **February 2024 - August 2024: Research Intern, 3D Visual Computing and Machine Intelligence (3DVICI) Lab, Institute for Interdisciplinary Information Sciences, Tsinghua University**
  * **Editing Human Videos for Robotic Skill Training**
    * Used video editing techniques to convert human hand-object interaction videos into robotic hand-object interaction videos.
    * Extracted 6D poses from human videos and compared human and robot data, referencing pipelines such as OpenVLA to evaluate the usefulness of human videos for robot training.

**Internship Experience**

* **February 2026 - May 2026: LLM Algorithm Intern, TRAE Intelligent Coding Algorithms, ByteDance**
  * **[Seed Code](https://seed.bytedance.com/zh/blog/seed2-0-%E6%AD%A3%E5%BC%8F%E5%8F%91%E5%B8%83) Model - Coding Capability Optimization** (MoE model with hundreds of billions of parameters, trained on hundreds of GPUs)
    * Systematically evaluated long-horizon coding performance on public and internal benchmarks, including LoCoBench and LoCoDiff, to identify gaps versus leading models.
    * Analyzed failure modes in code-state tracking and synthesized training data from real online TRAE trajectories, improving benchmark performance by approximately 8% to match GLM-5; integrated the pipeline into the model's RL training framework to support data synthesis from dynamic rollouts.
    * Built a systematic rubric-based evaluation framework for open-ended technical QA covering 10+ task types, 20+ domains, 6 general dimensions, and 4 task-specific dimensions; conducted targeted synthetic-data supervised fine-tuning on weak tasks, domains, and dimensions, narrowing the gap to GPT-5.2 by approximately 49% on a real-user QA dataset.

* **June 2025 - August 2025: Applied Research Intern, Code Intelligence Center, Technology and Engineering Group (TEG), Tencent**
  * **CodeLLM Applications for Cursor Prediction and Smart Rewrite - Project Lead**
    * Synthesized data for 5 cursor-prediction and 15 smart-rewrite scenarios, producing 21K high-quality training examples.
    * Conducted supervised fine-tuning and evaluation across Qwen2.5-Coder 0.5B/3B/7B/14B models; iterative improvements brought task performance on par with GPT-4.1.
    * Built a VS Code extension with real-time inference and visual interaction; the project ranked 1st among 5 teams.

**Course Project**

* **April 2025 - June 2025: Frontiers in AI Safety and Governance (Spring 2025)**
  * **Adaptive Safety Priming: Inference-Time Safeguards for Large Reasoning Models**
    * Developed Adaptive Safety Priming (ASP), a lightweight, dynamic safety mechanism that leverages the step-by-step inference process of large reasoning models to enable real-time intervention. This approach provides a more adaptive and resource-efficient path toward robustly safe models. [[Report](https://github.com/zhennan1/ASP/blob/main/Report.pdf)]

**Skills**

* **Programming:** C, C++, Python
* **Machine learning:** PyTorch, vLLM, VeRL, FSDP
* **Tools:** Git, Linux, Docker, LaTeX
* **English:** College English Test Band 6 (CET-6): 601/710

**Awards**

* Academic Excellence Scholarship, 2024-2025 Academic Year
* Tsinghua University Software Engineering Outstanding Project Award, 2024

<!--
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
-->

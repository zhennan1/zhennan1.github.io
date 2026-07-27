---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

_Last updated: July 2026_

**Education**

* **M.Eng. in Electronic Information (Computer Science and Technology), Tsinghua University, Expected June 2028**  
  
  * Advisor: Associate Professor [Jianfei Chen](https://ml.cs.tsinghua.edu.cn/~jianfei/)
  * Research group: [TSAIL](https://ml.cs.tsinghua.edu.cn/)

* **B.Eng. in Computer Science and Technology, Tsinghua University, June 2026**  
  
  * Relevant coursework (grade A or above): Ordinary Differential Equations; Probability and Statistics; Fundamentals of Programming; Programming and Training; Software Engineering; Operating Systems; Principles of Signal Processing; Database Special Topic Training
  * Previous major: Medicine. Transitioned to Computer Science to pursue a passion for artificial intelligence.

**Research Statement**

  * My research focuses on post-training and test-time scaling for large language models (LLMs), with the goal of improving model and agent capabilities in complex settings such as long-context reasoning, long-form generation, coding, and multi-agent collaboration.

**Publications**

* **Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration**  
  Zijun Liu\*, **Zhennan Wan\***, Peng Li, Ming Yan, Fei Huang, Yang Liu  
  ACL 2026 Main Conference, co-first author. [[Paper](https://arxiv.org/abs/2505.21471)] [[Code](https://github.com/THUNLP-MT/ExtAgents)] [[Data](https://huggingface.co/datasets/zhennan1/ExtAgents)]

**Research Experience**

* **September 2025 - Present: Research Member, Tsinghua Statistical Artificial Intelligence and Learning Group (TSAIL), Tsinghua University**
  * **LC-Zero: Self-Evolving Long-Context Reasoning from Zero Data**
    * Developing a zero-data synthesis pipeline that constructs short "worlds" containing questions, answers, and evidence, then expands them into long contexts.
    * The model learns from self-synthesized text to preserve correctness while continually increasing task difficulty; GRPO is used to enable self-evolving training (ongoing).
  * **Scaling Long-Form Story Generation with Structured Narrative State Tracking**
    * Proposed a tool-using agent framework that maintains structured narrative states to improve consistency in long-form fiction.
    * Scaled story generation from 10,000 to 100,000 words without noticeable performance degradation.

* **September 2024 - May 2025: Research Intern, Natural Language Processing and Social Humanities Computing Lab (THUNLP), Tsinghua University**
  * **Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration**
    * Developed ExtAgents, a multi-agent framework that distributes external knowledge across agents and enables intensive inter-agent communication, overcoming the input limits of a single LLM context window.
    * Matched or outperformed conventional approaches on knowledge-intensive question answering while achieving greater parallelism and scalability.

* **February 2024 - August 2024: Research Intern, 3D Visual Computing and Machine Intelligence (3DVICI) Lab, Institute for Interdisciplinary Information Sciences, Tsinghua University**
  * **Editing Human Videos for Robotic Skill Training**
    * Used video editing techniques to convert human hand-object interaction videos into robotic hand-object interaction videos.
    * Extracted 6D poses from human videos and compared human and robot data, referencing pipelines such as OpenVLA to evaluate the usefulness of human videos for robot training.

**Internship Experience**

* **February 2026 - May 2026: LLM Algorithm Intern, TRAE Intelligent Coding Algorithms, ByteDance**
  * **Seed Code Model - Coding Capability Optimization**
    * Systematically evaluated long-context coding performance on LoCoBench, LoCoDiff, and other benchmarks to identify gaps versus leading models.
    * Analyzed failures in code-state tracking and synthesized training data from online trajectories, improving benchmark performance by approximately 8% to match GLM-5.
    * Designed a rubric-based evaluation framework for open-ended technical QA and conducted targeted synthetic-data supervised fine-tuning, narrowing the gap to GPT-5.2 by approximately 49%.

* **June 2025 - August 2025: Applied Research Intern, Code Intelligence Center, Technology and Engineering Group (TEG), Tencent**
  * **CodeLLM Applications for Cursor Prediction and Smart Rewrite - Project Lead**
    * Synthesized data for 5 cursor-prediction and 15 smart-rewrite scenarios, producing 21K high-quality training examples.
    * Conducted supervised fine-tuning and evaluation across Qwen2.5-Coder 0.5B/3B/7B/14B models; iterative improvements outperformed GPT-4.1 on selected tasks.
    * Built a VS Code extension with real-time inference and visual interaction; the project ranked 1st among 5 teams.

**Course Project**

* **April 2025 - June 2025: Frontiers in AI Safety and Governance (Spring 2025)**
  * **Adaptive Safety Priming: Inference-Time Safeguards for Large Reasoning Models**
    * Developed Adaptive Safety Priming (ASP), a lightweight, dynamic safety mechanism that leverages the step-by-step inference process of large reasoning models to enable real-time intervention. This approach provides a more adaptive and resource-efficient path toward robustly safe models. [[Report](https://github.com/zhennan1/ASP/blob/main/Report.pdf)]

**Skills**

* **Programming:** C, C++, Python
* **Machine learning:** PyTorch, vLLM, VeRL
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

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Education**

* **Master of Engineering in Electronic Information (Computer Science and Technology), Tsinghua University, 2028.06 (expected)**
  * Advisor: Associate Professor [Jianfei Chen](https://ml.cs.tsinghua.edu.cn/~jianfei/)
  * Research Lab: [TSAIL](https://ml.cs.tsinghua.edu.cn/)
* **Bachelor of Engineering in Computer Science and Technology, Tsinghua University, 2026.06**
  * Relevant Coursework (Grade >= A): Ordinary Differential Equations; Probability and Statistics; Fundamentals of Programming; Programming and Training; Software Engineering; Operating Systems; Principles of Signal Processing; Database Special Topic Training
  * Previous Major: Medicine. Pivoted to Computer Science to pursue a passion for Artificial Intelligence.

**Research Statement**

* My research focuses on LLM post-training and test-time scaling, aiming to improve model and agent capabilities in complex settings such as long-context reasoning, long-form generation, coding, etc.

**Publications**

* **Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration**  
  Zijun Liu\*, **Zhennan Wan\***, Peng Li, Ming Yan, Ji Zhang, Fei Huang, Yang Liu  
  ACL 2026 Main Conference. [[Paper](https://arxiv.org/abs/2505.21471)] [[GitHub](https://github.com/THUNLP-MT/ExtAgents)] [[Data](https://huggingface.co/datasets/zhennan1/ExtAgents)]  
  \*Equal contribution.

**Research Experience**

* **September 2025 - Present: Tsinghua Statistical Artificial Intelligence & Learning Group, Tsinghua University (TSAIL)**
  * Advisor: Associate Professor [Jianfei Chen](https://ml.cs.tsinghua.edu.cn/~jianfei/)
  * Research Topic: Enhancing Long-Context Capability of LLMs with Synthetic Data
  * ① LC-Zero: Self-Evolving Long-Context Reasoning from Zero Data
  * High-quality long-context data is scarce; it's difficult to satisfy difficulty, correctness, and authenticity simultaneously
For long-context tasks, we synthesize all texts, questions, and answers entirely from scratch. Since the model fully masters its own synthesized texts, correctness is better guaranteed, and difficulty can be continuously increased, enabling self-evolution
  * ② Scaling Long-Form Story Generation with Structured Narrative State Tracking
  * Existing methods still suffer from notable consistency issues in long-form story generation and struggle to scale to true novel length
We propose maintaining structured narrative state via tool calls to improve consistency in story writing, scaling from 10,000 to 100,000 words without noticeable quality degradation
  * ③ We are also following research on visual reasoning, such as DeepSeek's Thinking with Visual Primitives

* **September 2024 - May 2025: Natural Language Processing Lab, Tsinghua University (THUNLP)**
  * Advisor: Associate Professor [Peng Li](https://lpeng.net/) and Professor [Yang Liu](https://nlp.csai.tsinghua.edu.cn/~ly/)
  * Research Topic: Scaling External Knowledge Input Beyond the Context Length of LLMs via Multi-Agent Collaboration
  * Developed a multi-agent framework, ExtAgents, to overcome the context window limitations of current large language models (LLMs) and enable better scalability in inference-time knowledge integration without longer-context training

* **February 2024 - August 2024: 3D Visual Computing and Machine Intelligence (3DVICI) Lab, Institute for Interdisciplinary Information Sciences (IIIS), Tsinghua University**
  * Advisor: Assistant Professor [Li Yi](https://ericyi.github.io/)
  * Research Topic: Editing Human Videos for Robotic Skill Training
  * Utilized video editing techniques to convert human hand-object interaction videos into robotic hand-object interaction videos; extracted 6D poses of human videos; compared human data with robot data, referencing pipelines such as OpenVLA, to validate the effectiveness of human videos for robotic training

* **July 2023 - August 2023: State Key Laboratory of Intelligent Technology and Systems, Department of Computer Science and Technology, Tsinghua University**
  * Advisor: Assistant Professor [Bin Fang](https://scholar.google.com/citations?user=5G47IcIAAAAJ&hl=zh-CN)
  * Research Topic: Human-Machine Collaborative Operation of Super-functional Prosthetic Hands
  * Trained neural network models to extract human hand movements from electromyographic signals of the human arm

**Internship Experience**

* **February 2026 - May 2026: Intelligent Code Algorithms, TRAE, Stone, ByteDance**
  * Project Topic: Seed Code model capability optimization
  * Role: LLM Algorithm Engineer
  * Evaluated long-context capabilities across multiple benchmarks and identified gaps with SOTA models
  * Analyzed failure modes in code-state tracking and improved performance via training on synthetic data from real trajectories
  * Designed rubric-based evaluations for open-ended technical QA and improved model performance with targeted synthetic data

* **June 2025 - August 2025: Code Intelligence Center, Technology and Engineering Group (TEG), Tencent**
  * Project Topic: Applying CodeLLMs for Cursor Prediction and Intelligent Rewriting
  * Role: LLM Algorithm Engineer (Project Lead)
  * Researched data synthesis algorithms for CodeLLMs on cursor prediction and intelligent rewrite tasks
  * Trained a CodeLLM-based fusion model to implement cursor prediction and intelligent rewrite suggestions during code editing
  * Our group was ranked 1st among 5 groups

**Course Project**

* **April 2025 - June 2025: Frontiers in AI safety and Governance (2025 Spring)**
  * Lecturer: Professor [Peng Cui](https://pengcui.thumedialab.com/)
  * Project Topic: Adaptive Safety Priming: Inference-Time Safeguards for Large Reasoning Models
  * Developed a lightweight and dynamic safety mechanism, Adaptive Safety Priming (ASP), for large reasoning models (LRM) at inference time, which leverages their step-by-step inference process to enable real-time intervention. This approach provides a more adaptive and resource efficient path to develop robustly safe models. [Report](https://github.com/zhennan1/ASP/blob/main/Report.pdf)
  
**Skills**

* Programming
  * C/C++, Python, Pytorch
* Tools
  * Git, Linux, Django, Docker, LaTeX
* Language
  * College English Test-6 (CET6): 601 / 710 (top 10% of the normative group)

**Awards**

* Academic Excellence Scholarship (2024-2025)
* Tsinghua University Software Engineering Outstanding Project Award (2024)

<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->

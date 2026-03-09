---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, University of Information Technology of Ho Chi Minh city (UIT), 2023 - 2026

Work experience
======
* July 2025 to now: **Machine Learning Engineer**
  * **Grab**
  * Built a multi-agent AI system to transform free-form user input into structured automation workflows (nodes and edges).
  * Implemented NODE-SELECTOR Agent to identify required node types and a RAG-based NODESCHEMA Agent to dynamically generate schemas using a vector database.
  * Developed NODE-CONSTRUCTOR Agent and EDGE-CONSTRUCTOR Agent to build workflow components, followed by a REFINE/JUDGE Agent for validation and correction. Integrated human-in-the-loop feedback.
  * Researched, optimized, and deployed Vision Language Models (VLLMs) for large-scale OCR tasks across Malaysia, the Philippines, Indonesia, and Vietnam for Merchants onboarding process to surpass 97% accuracy.
  * Achieved sub-2.5 second inference time per request through model and pipeline optimizations with Quantization, Qlora and VLLM serving.
  * Using AirFlow to schedule anual data embedding inject to PostgresQL.


* July 2023: **Research Assistant**
  * University of Information Technology of Ho Chi Minh city (UIT)
  * Duties included: Conducting 4 workshop research papers in NLP/LLM.
  * Supervisor: Dr. Dang Van Thin


  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

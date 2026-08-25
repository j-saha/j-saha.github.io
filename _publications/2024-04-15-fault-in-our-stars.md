---
title: "The Fault in our Stars: Quality Assessment of Code Generation Benchmarks"
collection: publications
category: conferences
permalink: /publication/2024-04-15-fault-in-our-stars
excerpt: 'A study of 3,566 prompts across 9 code generation benchmarks, showing widespread prompt-quality issues that measurably affect model performance and raise data-contamination concerns.'
date: 2024-04-15
venue: '24th IEEE International Conference on Source Code Analysis and Manipulation (SCAM 2024)'
paperurl: 'https://arxiv.org/abs/2404.10155'
citation: 'Mohammed Latif Siddiq, Simantika Dristi, Joy Saha, Joanna C. S. Santos. "The Fault in our Stars: Quality Assessment of Code Generation Benchmarks." <i>SCAM</i>, 2024.'
authors:
  - "Mohammed Latif Siddiq"
  - "Simantika Dristi"
  - "Joy Saha"
  - "Joanna C. S. Santos"
---

We conduct the first large-scale study of prompt quality in code generation benchmarks, analyzing 3,566 prompts drawn from 9 widely used benchmarks. We find that these benchmarks are heavily skewed toward Python coding exercises with limited contextual dependencies, and that many prompts contain quality issues such as spelling and grammatical errors and inconsistent documentation styles. Fixing these issues improves Python code generation performance, though gains are smaller for Java. Our analysis also surfaces potential data contamination in GPT-3.5-Turbo and CodeGen-2.5, raising questions about the trustworthiness of current benchmark-based evaluations.

[Read the paper on arXiv](https://arxiv.org/abs/2404.10155)

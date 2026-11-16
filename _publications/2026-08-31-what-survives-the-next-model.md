---
title: "What Survives the Next Model? Benchmarking LLM-Based Techniques Against Single-Prompts"
collection: publications
category: preprints
permalink: /publication/2026-08-31-what-survives-the-next-model
excerpt: 'Re-evaluating 35 LLM-based technique papers from ICSE 2026, we find that for 37%-63% of them, a single automatically generated prompt to a newer model matches or beats the heavily engineered original tool.'
date: 2026-08-31
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2609.00468'
citation: 'Nahian Salsabil, Joy Saha, Simantika Bhattacharjee Dristi, Nicholas Phair, Nusrat Jahan Mozumder, Matthew B. Dwyer, Sebastian Elbaum. "What Survives the Next Model? Benchmarking LLM-Based Techniques Against Single-Prompts." <i>arXiv preprint arXiv:2609.00468</i>, 2026.'
authors:
  - "Nahian Salsabil"
  - "Joy Saha"
  - "Simantika Bhattacharjee Dristi"
  - "Nicholas Phair"
  - "Nusrat Jahan Mozumder"
  - "Matthew B. Dwyer"
  - "Sebastian Elbaum"
---

The software engineering research community has enthusiastically embraced the integration of Large Language Models (LLMs) into complex techniques to solve a wide variety of tasks. However, the extent to which this investment is strategic remains unclear, as the native capabilities of successive frontier model generations can rapidly render existing techniques obsolete. To assess this research investment, we analyze 35 LLM-based technique papers from ICSE 2026. We evaluate whether their complex tools can be outperformed by the simplest possible alternative: a single, automatically generated prompt executed on a newer generation model, without any iterative refinement. We find that for between 37% and 63% papers, a newer model with a single prompt natively outperforms the heavily engineered tooling proposed just a year prior. We identify that constructive techniques like code generation or repair are more amenable to substitution by a single-prompt. We also identify a surviving set of papers relying on strategies that provide additional insights to the model where newer LLMs will amplify the proposed technique. Our findings raise questions about the cost-benefit proposition of techniques designed as workarounds to temporary model deficits and the need to focus on enduring challenges that scale synergistically with future model generations.

[Read the preprint on arXiv](https://arxiv.org/abs/2609.00468)

---
title: "NeuroSTAR: Neuro-symbolic Temporal Specification Formalization using Automata"
collection: publications
category: conferences
permalink: /publication/2026-10-01-neurostar-specification-formalization
excerpt: 'NeuroSTAR translates natural-language requirements into LTLf by combining diverse LLM-generated candidates with automata-based (DFA) comparison to find and fix behavioral disagreements, improving over the prior state of the art by 8-18 percentage points.'
date: 2026-10-01
venue: '49th IEEE/ACM International Conference on Software Engineering (ICSE 2027)'
paperurl: 'https://arxiv.org/abs/2609.03161'
citation: 'Joy Saha, Trey Woodlief, Sebastian Elbaum, Matthew B. Dwyer. "NeuroSTAR: Neuro-symbolic Temporal Specification Formalization using Automata." <i>ICSE</i>, 2027.'
authors:
  - "Joy Saha"
  - "Trey Woodlief"
  - "Sebastian Elbaum"
  - "Matthew B. Dwyer"
---

Translating natural-language requirements into Linear Temporal Logic over finite traces (LTLf) is a key step toward automated formal verification, but existing LLM-based approaches often capture only part of the intended meaning. NeuroSTAR is a neuro-symbolic NL-to-LTLf framework built on two ideas: multiple generators produce diverse LTLf candidates, and an automata-theoretic comparison over DFA traces exposes behavioral disagreements between candidates that then guide formula refinement. NeuroSTAR improves over the prior state of the art by 8-18 percentage points on unambiguous benchmarks. We also apply it to driving law text, a reference-free domain relevant to autonomous-vehicle specification, where NeuroSTAR captures the necessary temporal semantics in 83.9% of driving law sections.

[Read the paper on arXiv](https://arxiv.org/abs/2609.03161)

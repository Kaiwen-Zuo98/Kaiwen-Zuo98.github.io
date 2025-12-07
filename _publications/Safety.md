---
layout: pub
type: article
key: med-ai-safety-2508
title: >
  How to Make Medical AI Systems Safer? Simulating Vulnerabilities and Threats in Multimodal Medical RAG Systems
author: Kaiwen Zuo, Zelin Liu, Raman Dutt, Ziyang Wang, Zhongtian Sun, Fan Mo, Pietro Liò
correspondence: Pietro Liò and Fan Mo
abbr: ICASSP-2026
journal: arXiv preprint
arxiv: 2508.17215
year: 2025
selected: true
code: (optional — 若有项目代码可填)
abstract: >
  Large Vision–Language Models (LVLMs) augmented with Retrieval-Augmented Generation (RAG) are increasingly used in medical AI for improved factual grounding via external clinical image-text retrieval. However, this reliance introduces a significant attack surface. We propose MedThreatRAG, a novel multimodal poisoning framework that systematically probes vulnerabilities in medical RAG systems by injecting adversarial image-text pairs. A key innovation is a Cross-Modal Conflict Injection (CMCI) method, which embeds subtle semantic contradictions between medical images and their paired reports, degrading retrieval and generation by disrupting cross-modal alignment while remaining plausible enough to evade conventional filters. Evaluations on IU-Xray and MIMIC-CXR QA tasks show MedThreatRAG reduces answer F1 scores by up to 27.66% and lowers LLaVA-Med-1.5 F1 rates to as low as 51.36%, exposing serious security gaps in clinical RAG systems. We also propose guidelines to inform safer design of future multimodal medical RAG systems.
bibtex: >
  @article{zuo2025medai,
    title = {How to Make Medical AI Systems Safer? Simulating Vulnerabilities and Threats in Multimodal Medical RAG Systems},
    author = {Kaiwen Zuo and Zelin Liu and Raman Dutt and Ziyang Wang and Zhongtian Sun and Yeming Wang and Fan Mo and Pietro Liò},
    journal = {arXiv preprint},
    year = {2025},
    archivePrefix = {arXiv},
    eprint = {2508.17215}
  }
---

---
title: "MMViR: A Multi-Modal and Multi-Granularity Representation for Long-range Video Understanding"
collection: publications
permalink: /publication/2026-01-09-paper-mmvir-5
excerpt: 'This paper introduces MMViR, a novel multi-modal, multi-grained structured representation for long video understanding. MMViR identifies key turning points to segment the video and constructs a three-level description that couples global narratives with fine-grained visual details.'
date: 2026-01-09
paperurl: 'https://arxiv.org/abs/2601.05495'
author: Zizhong Li, Haopeng Zhang, Jiawei Zhang
---


**Abstract**

Long videos, ranging from minutes to hours, present significant challenges for current Multimodal Large Language Models (MLLMs) due to their complex events, diverse scenes, and long-range dependencies. Direct encoding of such videos is computationally too expensive, while simple video-to-text conversion often results in redundant or fragmented content. To address these limitations, we introduce MMViR, a novel multi-modal, multi-grained structured representation for long video understanding. MMViR identifies key turning points to segment the video and constructs a three-level description that couples global narratives with fine-grained visual details. This design supports efficient query-based retrieval and generalizes well across various scenarios. Extensive evaluations across three tasks, including QA, summarization, and retrieval, show that MMViR outperforms the prior strongest method, achieving a 19.67% improvement in hour-long video understanding while reducing processing latency to 45.4% of the original.

![MMViR](../images/MMViR_main.pdf "Overview of the MMViR and the downstream inference.")
<center>Overview of the MMViR and the downstream inference. Given a long video, MMViR leverages an MLLM to construct a multi-modal and multi-grained representation for it. The high-level timeline descriptions serve as a global semantic index, enabling efficient query-aware relevant clip localization. This design ensures a synergistic balance between global narrative coherence and fine-grained evidence, effectively addressing the computational challenges of long-form content.</center>

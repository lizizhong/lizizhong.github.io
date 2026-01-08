---
title: "Token-Level Precise Attack on RAG: Searching for the Best Alternatives to Mislead Generation"
collection: publications
permalink: /publication/2025-08-05-paper-rag-attack-number-4
excerpt: 'This paper proposes Token-level Precise Attack on the RAG (TPARAG), which leverages a lightweight white-box LLM as an attacker to generate and iteratively optimize malicious passages at the token level and is suitable for both white-box and black-box RAG systems.'
date: 2025-08-05
paperurl: 'https://arxiv.org/pdf/2508.03110'
author: Zizhong Li, Haopeng Zhang, Jiawei Zhang
---


**Abstract**

While large language models (LLMs) have achieved remarkable success in providing trustworthy responses for knowledge-intensive tasks, they still face critical limitations such as hallucinations and outdated knowledge. To address these issues, the retrieval-augmented generation (RAG) framework enhances LLMs with access to external knowledge via a retriever, enabling more accurate and real-time outputs about the latest events. However, this integration brings new security vulnerabilities: the risk that malicious content in the external database can be retrieved and used to manipulate model outputs. Although prior work has explored attacks on RAG systems, existing approaches either rely heavily on access to the retriever or fail to jointly consider both retrieval and generation stages, limiting their effectiveness, particularly in black-box scenarios. To overcome these limitations, we propose Token-level Precise Attack on the RAG (TPARAG), a novel framework that targets both white-box and black-box RAG systems. TPARAG leverages a lightweight white-box LLM as an attacker to generate and iteratively optimize malicious passages at the token level, ensuring both retrievability and high attack success in generation. Extensive experiments on open-domain QA datasets demonstrate that TPARAG consistently outperforms previous approaches in retrieval-stage and end-to-end attack effectiveness. These results further reveal critical vulnerabilities in RAG pipelines and offer new insights into improving their robustness.

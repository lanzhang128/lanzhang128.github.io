---
title: "Consistent Autoformalization for Constructing Mathematical Libraries"
collection: publications
permalink: /publication/emnlp2024
authors: "Lan Zhang, Xin Quan, Andre Freitas"
excerpt: "[Paper](https://aclanthology.org/2024.emnlp-main.233/)&nbsp;&nbsp;&nbsp;&nbsp;
          [Repository](https://github.com/lanzhang128/retrieval_augmented_autoformalization)"
date: 2024-11-13
venue: "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing"
citation: "Lan Zhang, Xin Quan, and Andre Freitas. 2024. Consistent Autoformalization for Constructing Mathematical Libraries. In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 4020–4033, Miami, Florida, USA. Association for Computational Linguistics."
---

**Abstract**

Autoformalization is the task of automatically translating mathematical content written in natural language to a formal language expression. The growing language interpretation capabilities of Large Language Models (LLMs), including in formal languages, are lowering the barriers for autoformalization. However, LLMs alone are not capable of consistently and reliably delivering autoformalization, in particular as the complexity and specialization of the target domain grows. As the field evolves into the direction of systematically applying autoformalization towards large mathematical libraries, the need to improve syntactic, terminological and semantic control increases. This paper proposes the coordinated use of three mechanisms, most-similar retrieval augmented generation (MS-RAG), denoising steps, and auto-correction with syntax error feedback (Auto-SEF) to improve autoformalization quality. The empirical analysis, across different models, demonstrates that these mechanisms can deliver autoformalizaton results which are syntactically, terminologically and semantically more consistent. These mechanisms can be applied across different LLMs and have shown to deliver improve results across different model types.

**BibTex citation:**

<div class="code-block">
  <pre><code id="code" class="language-python">
  @inproceedings{zhang-etal-2024-consistent,
    title = "Consistent Autoformalization for Constructing Mathematical Libraries",
    author = "Zhang, Lan  and
      Quan, Xin  and
      Freitas, Andre",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.233/",
    doi = "10.18653/v1/2024.emnlp-main.233",
    pages = "4020--4033"}
  </code></pre>
</div>

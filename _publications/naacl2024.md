---
title: "Multi-Operational Mathematical Derivations in Latent Space"
collection: publications
permalink: /publication/naacl2024
authors: "Marco Valentino, Jordan Meadows, Lan Zhang, Andre Freitas"
excerpt: "[Paper](https://aclanthology.org/2024.naacl-long.80/)"
date: 2024-06-16
venue: "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)"
citation: "Marco Valentino, Jordan Meadows, Lan Zhang, and Andre Freitas. 2024. Multi-Operational Mathematical Derivations in Latent Space. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers), pages 1446–1458, Mexico City, Mexico. Association for Computational Linguistics."
---

**Abstract**

This paper investigates the possibility of approximating multiple mathematical operations in latent space for expression derivation. To this end, we introduce different multi-operational representation paradigms, modelling mathematical operations as explicit geometric transformations. By leveraging a symbolic engine, we construct a large-scale dataset comprising 1.7M derivation steps stemming from 61K premises and 6 operators, analysing the properties of each paradigm when instantiated with state-of-the-art neural encoders.Specifically, we investigate how different encoding mechanisms can approximate expression manipulation in latent space, exploring the trade-off between learning different operators and specialising within single operations, as well as the ability to support multi-step derivations and out-of-distribution generalisation. Our empirical analysis reveals that the multi-operational paradigm is crucial for disentangling different operators, while discriminating the conclusions for a single operation is achievable in the original expression encoder. Moreover, we show that architectural choices can heavily affect the training dynamics, structural organisation, and generalisation of the latent space, resulting in significant variations across paradigms and classes of encoders.

**BibTex citation:**

<div class="code-block">
  <pre><code id="code" class="language-python">
  @inproceedings{valentino-etal-2024-multi-operational,
    title = "Multi-Operational Mathematical Derivations in Latent Space",
    author = "Valentino, Marco  and
      Meadows, Jordan  and
      Zhang, Lan  and
      Freitas, Andre",
    editor = "Duh, Kevin  and
      Gomez, Helena  and
      Bethard, Steven",
    booktitle = "Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.naacl-long.80",
    doi = "10.18653/v1/2024.naacl-long.80",
    pages = "1446--1458"}
  </code></pre>
</div>

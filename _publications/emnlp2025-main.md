---
title: "Autoformalization in the Wild: Assessing LLMs on Real-World Mathematical Definitions"
collection: publications
permalink: /publication/emnlp2025-main
authors: "Lan Zhang, Marco Valentino, Andre Freitas"
excerpt: "**Best Resource Paper Award**<br>
          [Paper](https://aclanthology.org/2025.emnlp-main.90/)&nbsp;&nbsp;&nbsp;&nbsp;
          [Repository](https://github.com/lanzhang128/definition_autoformalization)&nbsp;&nbsp;&nbsp;&nbsp;
          [Dataset](https://huggingface.co/datasets/lanzhang128/Definition-Autoformalization)"
date: 2025-11-5
venue: "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing"
citation: "Lan Zhang, Marco Valentino, and Andre Freitas. 2025. Autoformalization in the Wild: Assessing LLMs on Real-World Mathematical Definitions. In Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing, pages 1720–1738, Suzhou, China. Association for Computational Linguistics."
---

**Abstract**

Thanks to their linguistic capabilities, LLMs offer an opportunity to bridge the gap between informal mathematics and formal languages through autoformalization. However, it is still unclear how well LLMs generalize to sophisticated and naturally occurring mathematical statements. To address this gap, we investigate the task of autoformalizing real-world mathematical definitions: a critical component of mathematical discourse. Specifically, we introduce two novel resources for autoformalization, collecting definitions from Wikipedia (Def_Wiki) and arXiv papers (Def_ArXiv). We then systematically evaluate a range of LLMs, analyzing their ability to formalize definitions into Isabelle/HOL. Furthermore, we investigate strategies to enhance LLMs’ performance including refinement through external feedback from Proof Assistants, and formal definition grounding, where we augment LLMs’ formalizations through relevant contextual elements from formal mathematical libraries. Our findings reveal that definitions present a greater challenge compared to existing benchmarks, such as miniF2F. In particular, we found that LLMs still struggle with self-correction, and aligning with relevant mathematical libraries. At the same time, structured refinement methods and definition grounding strategies yield notable improvements of up to 16% on self-correction capabilities and 43% on the reduction of undefined errors, highlighting promising directions for enhancing LLM-based autoformalization in real-world scenarios.

**BibTex citation:**

<div class="code-block">
  <pre><code id="code" class="language-python">
  @inproceedings{zhang-etal-2025-autoformalization,
    title = "Autoformalization in the Wild: Assessing {LLM}s on Real-World Mathematical Definitions",
    author = "Zhang, Lan  and
      Valentino, Marco  and
      Freitas, Andre",
    editor = "Christodoulopoulos, Christos  and
      Chakraborty, Tanmoy  and
      Rose, Carolyn  and
      Peng, Violet",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2025",
    address = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.emnlp-main.90/",
    doi = "10.18653/v1/2025.emnlp-main.90",
    pages = "1720--1738",
    ISBN = "979-8-89176-332-6"}
  </code></pre>
</div>

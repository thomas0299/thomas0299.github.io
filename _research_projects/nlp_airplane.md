---
title: "Few-Shot Prompting for Flexible Classification of Operator Texts in Multilingual Aircraft Manufacturing ✈️"
permalink: /research_projects/nlp_airplane
excerpt: 'NLP Project'
date: 2025-07-01
---

<center><img src="/images/research_projects/nlp_airplane.png" width="600" height="600" /></center>

Unstructured textual data from manufacturing environments presents significant challenges for automated processing, particularly due to domain-specific jargon and abbreviations used by operators. We investigate the use of zero and few-shot prompting with open-source Large Language Models (LLMs) to classify operator-generated texts in aircraft manufacturing under data-scarce, high-variation conditions. Our experiments focus on English and Chinese operator texts, simulating three real-world technical shorthand scenarios, and evaluate four models: Mistral, Llama, Gemma, and Qwen. We show that Gemma and Mistral consistently delivers the highest few-shot accuracy for English and that providing additional examples beyond a small set yields diminishing returns. Moreover, few-shot prompts not only accelerate response times compared to zero-shot but also maintain accuracy, whereas Llama and Qwen tend to hallucinate or deviate from exact expected outputs when example counts exceed a critical threshold. When handling Chinese text, Mistral struggles to accurately recover short abbreviations. These results identify a practical “sweet spot” of 3–12 examples for deploying lightweight, locally deployable NLP tools in industrial settings, balancing accuracy, speed, and reliability.

Pierrick Bougault, Thomas Adler

* [Poster](https://drive.google.com/file/d/11IlFvuD-aPthsviJWUZeMqWB_3_A_VL8/view?usp=sharing)

* [Report](https://drive.google.com/file/d/1Idjxjbfjky8CAcG7nL-PknaOMdWVS4fb/view?usp=sharing)


<center><img src="/images/cv/th1.png" width="350" height="350" /></center>

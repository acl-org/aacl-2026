---
title: Tutorials
layout: single
excerpt: "AACL-IJCNLP 2026 Tutorials."
permalink: /program/tutorials/
toc: true
toc_sticky: true
toc_icon: "cog"
sidebar:
    nav: program
---

The following 7 tutorials will be offered at AACL-IJCNLP 2026. Tutorial dates and times will be announced soon.

## A Tutorial on Measurement Science for Language Model Evaluation

* Instructors: Sang Truong, Rudy Corona, Serena Wang, Sanmi Koyejo
* Website: [https://aimslab.stanford.edu/tutorial](https://aimslab.stanford.edu/tutorial)

As language models are increasingly optimized against the benchmarks used to evaluate them and deployed across diverse global populations, the assumptions behind evaluation are quietly breaking down. This tutorial focuses on a scientific approach for language model evaluation: a measurement-theoretic framework that treats LLM evaluation as a scientific measurement problem. We organize three hours around the classical structure of a measurement instrument and give NLP researchers usable tools for each part: (1) validity—when a benchmark score actually measures the capability it claims to, with emphasis on cross-cultural and cross-lingual transfer; (2) predictive measurement—inferring capability efficiently from sparse data via latent-variable models and cold-start prediction; and (3) design and incentives—why some benchmarks are gameable and what mechanisms improve robustness under explicit assumptions about evaluator access, developer objectives, and information leakage. The tutorial connects language model evaluation, latent-variable modeling, and mechanism design, three literatures that NLP researchers rarely encounter together, and equips the audience to build and interpret evaluations that remain trustworthy under deployment and strategic pressure.

## AI Scientist: Persistent Scientific Systems with Memory, Verification, and Human Governance

* Instructors: Hejia Geng, Wanghan Xu, Yifan Zhou, Zhenfei Yin, Yingcheng Wu, Philip Torr
* Website: [https://yyifan-onyen.github.io/ai_scientist/](https://yyifan-onyen.github.io/ai_scientist/)

AI Scientists are evolving from autonomous workflow agents that automate a research pipeline into persistent scientific systems that maintain long-horizon research state, verify novelty against prior work, track experimental provenance, execute in real or simulated laboratories, and collaborate with human scientists. As new systems, benchmarks, and infrastructure proliferate across NLP, machine learning, and the natural sciences, the associated literature has become fragmented across communities that adopt different vocabularies for the same concepts. This cutting-edge tutorial provides a comprehensive overview of AI Scientist research, organizing representative work around six recurring concerns: persistent scientific state, literature-grounded novelty verification, scientific infrastructure and execution environments, embodied scientific interaction, reliability and provenance, and human governance. For each concern, we trace the transition from early end-to-end pipelines to recent persistent-system designs, together with the evaluation methodology used to measure progress. Attendees will leave with a compact field map, a reusable vocabulary that separates agent architecture from scientific infrastructure, an annotated reading list, a hands-on AI Scientist loop, and a set of open problems on which NLP researchers can have immediate impact. All materials are available at [https://yyifan-onyen.github.io/ai_scientist/](https://yyifan-onyen.github.io/ai_scientist/).

## Code-Switching for Multilingual LLMs

* Instructors: Juhyun Oh, Alice Oh, Thamar Solorio, Haneul Yoo, Genta Indra Winata, Ruochen Zhang
* Website: [https://sites.google.com/view/code-switching-tutorial/](https://sites.google.com/view/code-switching-tutorial/)

This tutorial provides a structured overview of code-switching for multilingual large language models (LLMs), connecting linguistic theory, NLP methodology, and human-centered perspectives. Code-switching is a natural communicative practice among multilingual speakers and is increasingly central to LLM interactions, where users bring mixed-language practices to prompts and models themselves may produce mixed-language outputs. The tutorial will cover theoretical foundations from sociolinguistics, code-switching behavior in human-AI interaction, datasets and evaluation benchmarks, synthetic data generation, multilingual LLM training and inference, mechanistic interpretability of unintended language switching, speech and multimodal code-switching, and societal impacts. By synthesizing work across NLP, linguistics, HCI, speech processing, and multilingual communities, the tutorial aims to give participants a coherent view of the field and identify open challenges for building multilingual LLMs that better reflect how multilingual users actually communicate.

## Diffusion Language Models: Foundations and Frontiers of Non-Autoregressive Language Generation

* Instructors: Daisuke Oba, Danushka Bollegala
* Website: [https://dllm-aacl.github.io/](https://dllm-aacl.github.io/)

Diffusion language models (DLMs) have recently emerged as a non-autoregressive approach to language generation, enabling parallel, iterative, and refinement-based decoding beyond the conventional left-to-right paradigm. This tutorial offers the NLP community a technical map of this emerging field: starting from diffusion formulations for text, we clarify their connections to autoregressive language modeling, masked language modeling, and earlier iterative generation methods. We then survey recent progress in large-scale DLMs, efficient inference, training objectives, and post-training, including reinforcement learning for reasoning and alignment. Throughout the tutorial, we treat DLMs not as a solved replacement for autoregressive language models, but as a rapidly developing paradigm whose efficiency claims, controllability, practical assessment, and deployment implications require careful examination. We close by discussing representative open directions, from broader formulations such as flow-based language modeling to reliability, safety, and social bias as key requirements for the social acceptability of DLMs.

## From Retrieval-Augmented Generation (RAG) to Agentic Deep Research

* Instructors: Luna Dong, Sanat Sharma, Xiao Yang, Jiaqi Wang, Kai Sun, Yinglong Xia, Scott Yih
* Website: [https://papers.lunadong.com/tutorial](https://papers.lunadong.com/tutorial)

Despite well-known hallucination issues, LLMs have become an increasingly indispensable source of information, and the underlying technology has advanced rapidly to make their answers far more reliable. Early on, Retrieval-Augmented Generation (RAG) emerged as the dominant remedy, grounding LLM responses in external knowledge and evolving from simple retrieve-then-read pipelines into modular, graph-enhanced, and agentic systems. More recently, Agentic Deep Research has pushed the frontier further, equipping LLMs with autonomous planning, multi-hop investigation, and iterative synthesis to tackle open-ended questions that no single retrieval pass can answer. This tutorial offers an in-depth treatment of modern RAG and Deep Research, grounded in an AI-assisted systematic analysis of 2,000+ recent papers (2020–2026). Attendees will leave with a structured roadmap, evidence-backed practical recommendations, and a clear map of open research opportunities.

## Post-Deployment Self-Improving Language Agents: Learning, Memory, and Adaptation

* Instructors: Estevam Hruschka
* Website: [https://megagon.ai/aacl_tutorial2026/](https://megagon.ai/aacl_tutorial2026/)

LLM-based systems are increasingly deployed as language agents: long-running NLP systems that retrieve information, call tools, maintain memory, interact with users, and operate in changing environments. After deployment, these systems must contend with evolving user goals, updated knowledge sources, shifting APIs, new tasks, and previously unseen failure modes. Yet adaptation is still often handled through an ad hoc combination of prompt changes, periodic fine-tuning, retrieval updates, memory mechanisms, and manual intervention. The tutorial examines how post-deployment NLP systems can instead be designed as self-improving language agents, drawing on never-ending learning, lifelong learning, continual learning, and recent advances in agentic AI. We take a system-level view of learning: improvement may arise not only from changes to model parameters, but also from persistent changes to memory, knowledge, tools, policies, and other components of the agent and its harness. The tutorial combines literature review with practical running examples (code provided) illustrating different forms of post-deployment learning. We'll examine empirical results and failure cases to understand when adaptation improves a system, when it doesn't, and how such changes can be evaluated. We'll cover a broader transition in NLP: from increasingly capable static models toward developing language systems that can continue to learn and improve responsibly throughout their deployed lifetime.

## The Future of NLP Needs Ethical Considerations: An Interactive Tutorial for Researchers and Students

* Instructors: Min-Yen Kan, Barid Xi Ai, Esther Gan, Yisong Miao, Abdoul Jalil Djiberou Mahamadou, Seunghun Lee, Margot Mieskes, Adriana Pagano, Monojit Choudhury, Vamshi Krishna Bonagiri
* Website: [https://ethics.aclweb.org/tutorials/AACL-IJCNLP_2026/](https://ethics.aclweb.org/tutorials/AACL-IJCNLP_2026/)

With NLP research being rapidly productionized into real-world applications, it is important to be aware of and think through the consequences of our work. Such ethical considerations are important in both senior and junior roles of researchers and students (e.g. privacy, consent, fairness, among others). This tutorial will equip participants with basic guidelines for thinking deeply about ethical issues and review common considerations that recur in NLP research. The methodology is interactive and participatory, including discussion and group work related to case studies that involve bias and broader issues (e.g., environmental impact). Participants will gain practical experience on when to flag a paper for ethics review and how to write an ethical consideration section to be shared with the broader community. Most importantly, the participants will be co-creating the tutorial outcomes and extending tutorial materials to share as public outcomes.

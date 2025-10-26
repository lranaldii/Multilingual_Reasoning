# Multilingual Reasoning in Large Language Models: Inference, Fine-Tuning, and Pre-Training Beyond English


## Overview  
This tutorial addresses the challenge of reasoning in large language models (LLMs) beyond the English paradigm. It presents a framework for **multilingual reasoning**, defined as the transfer and alignment of reasoning processes across languages, rather than mere translation or output generation in multiple languages. The tutorial is structured across three core levels:  

- Inference-time techniques (reasoning without training)  
- Fine-tuning regimes (internalising multilingual reasoning)  
- Pre-training interventions (towards reasoning equity across languages)  

Participants will gain both conceptual grounding and hands-on workflows (prompt cards, pipelines, demo notebooks) to move from English-centric reasoning to globally equitable multilingual reasoning.

---

## Tutorial Structure  

### Module 0 – Foundations for Multilingual Reasoning  
- Theoretical grounding: language-agnostic inference, structural transfer, cultural robustness  
- Evaluation frameworks: cross-lingual consistency, cultural validity, faithfulness  
- Interpretability as a diagnostic for language-specific vs. language-agnostic mechanisms  

### Module A – Inference-Time Techniques (Reasoning Without Training)  
- Translate-as-tool: strengths and limitations in low-resource settings  
- Alignment-first prompting across languages  
- Cross-lingual self-consistency: contradiction detection & self-correction  
- Decision checklists: resource- and typology-aware ablations  

### Module B – Fine-Tuning Regimes (Internalising Multilingual Reasoning)  
- Multilingual instruction-tuning and preference alignment  
- Structure-preserving distillation from English reasoning models  
- Hybrid pipelines: DPO/GRPO optimisation  
- Parameter-efficient adaptation (e.g., LoRA, adapters) and model merging  
- Latent-space disentanglement/abstraction for language-agnostic reasoning  

### Module C – Pre-Training Interventions (Towards Reasoning Equity)  
- Balanced multilingual & multimodal pre-training (e.g., EuroLLM, Salamandra)  
- Typology- and curriculum-aware data selection  
- Continual pre-training and monitoring model capacity degradation  
- Design heuristics for reasoning equity across scripts and languages  

### Applications – Reproducible Workflows  
- Prompt-cards for alignment-first elicitation  
- Instruction- & preference-alignment pipelines  
- Continuous multilingual pre-training toy environment  
- Cross-language evaluation demo notebooks  

---

## Schedule (3-hour tutorial)  

| Session       | Topic                                   | Duration   |
|---------------|------------------------------------------|------------|
| Introduction  | Motivation & Foundations                 | 30 mins    |
| Session 1     | Inference-Time Techniques                | 40 mins    |
| Session 2     | Fine-Tuning Regimes                      | 40 mins    |
| Session 3     | Pre-Training Interventions               | 40 mins    |
| Conclusion    | Applications, Q&A, Future Directions     | 30 mins    |

---

## Reading List  

### Surveys & Foundational Works(*)  
- Qin et al., *Multilingual Large Language Models: A Survey of Resources, Taxonomy and Frontiers*, 2024  
- Xu et al., *A Survey on Multilingual Large Language Models: Corpora, Alignment and Bias*, 2025  
- Huang & Chang, *Towards Reasoning in Large Language Models: A Survey*, 2023  
- Ghosh et al., *A Survey of Multilingual Reasoning in Language Models*, 2025  

### Inference-Time & Prompting(*)  
- Qin et al., *Cross-Lingual Prompting: Improving Zero-Shot Chain-of-Thought Reasoning across Languages*, EMNLP 2023  
- Zhu et al., *Question Translation Training for Better Multilingual Reasoning*, Findings of ACL 2024  
- Ranaldi et al., *Empowering Multi-step Reasoning across Languages via Program-Aided LMs*, EMNLP 2024  

### Fine-Tuning & Alignment(*)  
- Lai & Nissim, *mCoT: Multilingual Instruction-Tuning for Reasoning Consistency*, ACL 2024  
- She et al., *MAPO: Multilingual Alignment-as-Preference Optimisation*, ACL 2024  
- Dang et al., *RLHF Can Speak Many Languages*, EMNLP 2024  
- Ranaldi & Pucci, *Multilingual Reasoning via Self-Training*, NAACL 2025  

### Pre-Training & Data Equity(*)  
- Martins et al., *EuroLLM*, Procedia Computer Science 2025  
- Gonzalez-Agirre et al., *Salamandra Technical Report*, 2025  
- Burchell et al., *HPLT Dataset for High-Performance Language Technologies*, ACL 2025  

### Evaluation & Interpretability(*)  
- Qi et al., *Cross-Lingual Consistency of Factual Knowledge*, EMNLP 2023  
- Tang et al., *Language-Specific Neurons: The Key to Multilingual Capabilities*, ACL 2024  
- Zhao & Aletras, *Comparing Explanation Faithfulness Between Multilingual and Monolingual LMs*, NAACL 2024

>(*)This repository is an **active work in progress**. Additional notebooks, extended reading lists, and recent papers capturing the evolving **state of the art in multilingual reasoning** will be integrated. The current version provides the initial conceptual and scaffolding to be expanded with new papers, datasets, models, and protocols (**note** that the submitted version of the proposal contains a magigor overview which will be augmented here as well).

---

## Prerequisites  
Attendees are expected to have a general understanding of large language models, fine-tuning methods and basic evaluation in NLP. No specific prior experience in multilingual reasoning is required.

---

## Diversity & Ethics  
This tutorial is organised by a multidisciplinary, multilingual team and explicitly promotes linguistic equity and cultural robustness in AI systems. We emphasise inclusive perspectives across languages, cultures and research traditions, aiming to advance reasoning models that are globally accessible and fair.

---

## Materials & Repository  
All slides, demo notebooks and workflow materials will be publicly released at:  
👉 [github.com/lranaldii/Multilingual_Reasoning/demo](https://github.com/lranaldii/Multilingual_Reasoning/demo)  


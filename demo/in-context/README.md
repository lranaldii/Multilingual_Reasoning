# Module A — In-Context Techniques (Reasoning Without Training)

This module shows how **prompting strategies** to improve multilingual reasoning *without retraining* the model.  
It contains one notebook: `demo_in_context.ipynb`.

---

## Objectives

To explore simple, reproducible ways to:
1. **Elicit structured reasoning** through *alignment-first* prompts.  
2. **Compare reasoning across languages** via *cross-lingual self-consistency*.  
3. **Test translation effects** by contrasting *native-language* vs *pivot-through-English* reasoning.

These small experiments help visualise how reasoning coherence can vary across languages even in zero-shot conditions.

---

## 📘 Notebook Overview

| Section | Purpose |
|----------|----------|
| **1 · Setup** | Choose *full* mode or *fallback* mock mode (no internet). |
| **2 · Prompt Cards** | Prompt templates for alignment-first reasoning. |
| **3 · Cross-lingual Self-Consistency** | Generate reasoning in several languages and compute agreement. |
| **4 · Translation Ablation** | Compare outputs obtained directly in the target language vs via English pivot. |
| **5 · Quick Summary** | Print agreement %, contradictions list, and example outputs. |

---

## ⚙️ Quick Start

```bash
pip install -U transformers pandas


# Module C — Pre-Training Interventions (Towards Reasoning Equity)

This module explores how **multilingual pre-training choices** influence **reasoning parity** and **language stability** across languages.  
It simulates *continual pre-training* over miniature multilingual corpora and monitors *cross-language drift* in model performance.

---

## Objectives

- Simulate **continual pre-training phases** over small corpora in different languages.  
- Compare **sampling policies** (balanced vs skewed) to study data exposure imbalance.  
- Track **per-language loss** over training phases as a simple indicator of **reasoning drift** or **forgetting**.  
- Provide two fully reproducible **backends**:

| Backend | Description | Requirements |
|----------|--------------|---------------|
| **Full** | Tiny Masked Language Model (MLM) fine-tuning with `prajjwal1/bert-tiny` | `transformers`, `datasets`, `torch` |
| **Fallback** | Character 3-gram language model computing per-language NLL | none |

> *This module is purely didactic. It runs in a few minutes and aims to build intuition about the balance of multilingual data.*

---

## Notebook Overview (`toy_cpt_pretraining.ipynb`)

| Section | Purpose |
|----------|----------|
| **1 · Setup** | Define corpora, phases, and mode (Full or Fallback). |
| **2 · Sampling Policies** | Generate balanced and skewed batches across languages. |
| **3 · Full Backend (MLM)** | Short masked-LM fine-tuning and per-language evaluation. |
| **4 · Fallback Backend (n-gram)** | Offline simulation using character-level language model. |
| **5 · Drift Dashboard** | Plot loss per language across phases and export a CSV log. |

---

# Module B — Fine-Tuning Regimes (Internalising Multilingual Reasoning)

This module demonstrates how **instruction and preference alignment** can help models internalise multilingual reasoning behaviour, even with very small synthetic datasets.

It complements *Module A (in-context reasoning)* by moving from *prompt-based control* to *parameter-level adaptation*, showing how structured reasoning formats can be reinforced through fine-tuning signals.

---

## Objectives

To illustrate — in a lightweight, fully reproducible way — how to:

1. **Generate synthetic multilingual instructions** (English · Italian · Spanish · Chinese).  
2. **Perform simple supervised fine-tuning (SFT)** to align outputs with structured reasoning traces.  
3. **Simulate preference alignment** using a small reward based on structure validity.  
4. **Evaluate reasoning quality** via a *structure-validity rate* and a *distillation-style score*.

No heavy computing or dataset download is required. The code runs in under 3 minutes in fallback mode.

---

## Notebook Overview (`pipeline_finetune.ipynb`)

| Section | Purpose |
|----------|----------|
| **1 · Setup** | Choose between *full* mode (Transformers + PEFT) and *fallback* mode (pure Python). |
| **2 · Synthetic Dataset** | Create a toy multilingual dataset of reasoning problems and target answers. |
| **3 · Structure Validation** | Define simple regex-based checks for “well-formed” reasoning steps. |
| **4 · Fine-Tuning Loop** | Imitate SFT or preference alignment to bias the model toward structured outputs. |
| **5 · Evaluation** | Compute per-language structure validity and average reasoning consistency. |

---


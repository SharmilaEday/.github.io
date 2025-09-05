---
title: "Transformer-based NLP for Intent Classification"
excerpt: "Fine-tuned DistilBERT; 4.3% absolute accuracy lift vs. baseline; exported to TorchScript."
permalink: /projects/transformer-intent/
header:
  overlay_image: /assets/img/og-image.png
  overlay_filter: 0.35
badges:
  - label: "NLP"
  - label: "Transformers"
  - label: "PyTorch"
links:
  - label: "Code"
    url: "https://github.com/yourusername/intent-classifier"
  - label: "Report"
    url: "#"
---

**Problem:** Classify customer intents in support tickets.  
**Approach:** Fine-tuned DistilBERT with class-weighted loss.  
**Results:** Macro F1 ↑ from 0.78 → 0.85; latency 12ms per request on GPU; 45ms on CPU.  
**Impact:** Improved auto-routing precision; reduced manual triage.

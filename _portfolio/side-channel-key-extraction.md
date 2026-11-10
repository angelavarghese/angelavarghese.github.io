---
title: "Automated Cryptographic Key Extraction via Side-Channel Analysis"
excerpt: "Deep-learning attack that recovers all 16 AES-128 key bytes from power traces."
collection: portfolio
date: 2026-06-01
---

A deep-learning side-channel attack that recovers AES-128 keys from power traces.

**Stack:** Python, TensorFlow, TinyAES dataset

**Approach**
- A compact **CNN** predicts key-byte information from the traces.
- **Per-byte SNR peak windowing** selects the most informative parts of each trace.
- **Log-likelihood key ranking** combines predictions across traces.

**Result:** all **16 of 16 key bytes** recovered.

[Draft paper](URL) · [Code](URL)  

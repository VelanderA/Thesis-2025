# Thesis-2025
# Controlled Text generation through Task Vectors

This repository contains the code and experiments from our study on **task vectors** — defined as the difference in weights between a pretrained language model and its finetuned counterpart — and how they can be used to modulate model behavior in a controlled and interpretable way.

## 🧠 Overview

We explore how task vectors can be:

- **Scaled** to adjust model behaviors (e.g., toxicity, fluency, stylistic content).
- **Combined** to compose multiple behavioral traits in a predictable, additive fashion.

Our findings demonstrate that task vectors define a **semantically meaningful and partially navigable subspace** for guiding language model outputs.

## 🔍 Key Findings

- **Monotonic Scaling Effects**: Behavioral traits (e.g., tone, style) shift consistently with vector scaling.
- **Non-linear Toxicity Response**: Toxicity increases non-linearly with positive scaling.
- **Fluency Retention**: Outputs remain fluent with small-to-moderate scaling.
- **Stable Perplexity Range**: Perplexity stays relatively stable within an effective scaling range—our identified "sweet spot".
- **Composable Behaviors**: Adding multiple task vectors results in additive effects, enabling predictable modulation.

## 📈 Use Cases

This approach enables:
- Safer and more controllable text generation.
- Transparent and interpretable fine-tuning.
- Modular composition of model behaviors.
- Custom language model outputs aligned with user intent.

## Contact
For questions or collaboration inquiries, please contact anneth.velander@gmail.com.

## Citation
If you use this work, please cite:
```bibtex
@inproceedings{some_address_to_diva2025,
  title     = {Controlled Text generation through Task Vectors},
  author    = {Anneth Velander},
  year      = {2025},
}

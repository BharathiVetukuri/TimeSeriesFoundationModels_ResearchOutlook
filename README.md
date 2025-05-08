# Structured Intelligence: A Comprehensive Survey of Foundation Models for Time Series

**Author:** Soumya Bharathi Vetukuri, 016668964  

**Paper Reviewed:** [Ye et al., 2024 - A Survey of Time Series Foundation Models](https://arxiv.org/pdf/2405.02358)

---
## Submission Artifacts

| Artifact | Link |
|---------|------|
| Medium Article | [Read the article](https://medium.com/@soumyabharathi.vetukuri/structured-intelligence-a-comprehensive-survey-of-foundation-models-and-research-outlook-3d85ce6469b7) |
| Video Demo | [Watch on YouTube](https://youtu.be/GQZ-6vpdrr8) |
| Slide Deck | [Presentation Deck](https://www.slideshare.net/secret/2viGFmeiIFm7vU) |
| Source Paper | [Ye et al., 2024](https://arxiv.org/pdf/2405.02358) |

---
### Click here to Watch Youtube Video:

[![MediumArticle](https://img.youtube.com/vi/GQZ-6vpdrr8/0.jpg)](https://www.youtube.com/watch?v=GQZ-6vpdrr8)

---

## What’s This About?

> "If time is money, then time series data is your bank statement — structured, regular, and full of patterns."

Foundation models like GPT have transformed text and vision tasks. But can these general-purpose AI models also handle **structured time-dependent data** like ECG signals, stock charts, or energy usage?

This short story explores the 2024 survey paper by Ye et al., which analyzes how foundation models are being applied to **time series data** — one of the most underexplored yet ubiquitous data modalities.

---

## Key Takeaways from the Survey

### Two Main Paths:
1. **Pretrained Foundation Models for Time Series**  
   - e.g., **TimeGPT**, **TimesFM**, **GTT**  
   - Trained from scratch on large time series corpora  
   - Face limitations due to lack of large-scale datasets

2. **Adapted LLMs for Time Series Tasks**  
   - LLMs (e.g., GPT-2, GPT-3.5) fine-tuned or prompted  
   - **Embedding-visible** or **Text-visible** paradigms  
   - Tools: **TimeLLM**, **PromptCast**, **LLMF**, **LLM-Mob**

---

### Evaluated via the 3E Framework:
| Effectiveness | Efficiency | Explainability |
|---------------|------------|----------------|
| Accuracy across tasks (forecasting, classification, anomaly detection) | Training/inference costs, tuning strategy | Can humans understand and trust predictions? |

---

### Time Series Tasks Handled:
- **Classification**
- **Forecasting**
- **Imputation**
- **Anomaly Detection**

---

### Techniques & Tools:
- **Data Augmentation:** jittering, cropping, patching
- **Architectures:** Transformer (Encoder/Decoder/Hybrid)
- **Tuning Strategies:** Full Fine-Tuning, LoRA, Adapters, Prompt Tuning

---

### Real-World Domains:
- **Finance** (TDML, CIGN): Stock prediction + metadata
- **Healthcare** (METS, LLMF): ECG + Clinical reports
- **Traffic** (LLMST, AuxMobLCast): Human mobility patterns
- **Energy** (UMEF): Load forecasting with prompt-enhanced inputs

---

###  Research Gaps:
- Lack of ImageNet-scale time series datasets
- Weak cross-domain generalization
- Limited multimodal modeling (text + time + graph)
- Explainability remains immature in embedding-visible LLMs

---


## Citation

> Ye, Jiexia, et al. "A Survey of Time Series Foundation Models." arXiv preprint arXiv:2405.02358 (2024).  
> [arxiv.org/abs/2405.02358](https://arxiv.org/abs/2405.02358)

---

## Acknowledgments

- Special thanks to **Prof. Vijay Eranti / Samarth Sharma** for the guidance  
- Visual assets created with [DALL·E + PPT]  
- Inspiration and tools sourced from:
  - [Awesome TimeSeries LLM FM](https://github.com/start2020/Awesome-TimeSeries-LLM-FM)
  - [Treasure of Transformers](https://github.com/ashishpatel26/Treasure-of-Transformers)

---

## How to Reproduce or Extend

If you have come across relevant resources, feel free to open an issue or submit a pull request.

You’re welcome to clone this repo and:
- Add your own time series foundation model experiment
- Extend with benchmarking using datasets adding `/data` to the repository
- Replace illustrations with your own

```bash
git clone https://github.com/yourusername/time-series-foundation-models-review.git

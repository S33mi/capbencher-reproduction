# CapBencher Reproduction & Experiments

**Reproducing and extending** [CapBencher: Give Your LLM Benchmark a Built-in Alarm for Test-Set Overfitting](https://arxiv.org/abs/2505.18102) (ICML 2026).

CapBencher deliberately caps the best achievable accuracy on an LLM benchmark. Any model that scores **significantly above** that cap becomes a black-box alarm for data contamination or leaderboard hacking.

This repo tracks my hands-on reproduction, experiments, and extensions as part of my LLM learning journey.

---

## Goals

| Phase | Status | Description |
|-------|--------|-------------|
| **1. Colab Reproduction** | ✅ Done | Fully working Colab notebook that loads public capped datasets, runs the binomial test, and shows how to create your own capped benchmark |
| **2. Reproduce the Alarm** | 🔄 Next | Continual pretraining on capped data → watch accuracy cross the Bayes cap |
| **3. Cap My Own Benchmark** | 🔜 Planned | Apply CapBencher to a real dataset and release a public capped version |
| **4. Extensions** | 💡 Ideas | Cross-lingual checks, stronger statistical tests, private leaderboard integration |

---

## Quick Start

Open the notebook in Colab:

➡️ [notebooks/CapBencher_Colab_Reproduction.ipynb](notebooks/CapBencher_Colab_Reproduction.ipynb)

---

## Official Resources

| Resource | Link |
|----------|------|
| Paper | https://arxiv.org/abs/2505.18102 |
| Official Code | https://github.com/ishida-lab/capbencher |
| Public Datasets | https://huggingface.co/datasets/ishidalab/capbencher |
| Blog | https://ishida-lab.github.io/blog_capbencher.html |

---

## Related

Part of my [Modern AI & LLM Journey](https://github.com/S33mi/modern-ai-llm-journey).

---

## License

MIT

## 🌟 My Projects

Explore my public repositories showcasing various projects and implementations:
- [Conference Paper](https://github.com/Adam-yni/reliability): Repository containing the article titled: **When Are Customers Willing To Pay For Better Reliability, And How Much? - An Empirical Study On E-Commerce Observational Data Through Causal Inference And Natural Language Processing**, published for the ESREL 2024 conference, which I presented in Poland during the summer of 2024.
- [LLM Reasoning FineTuning](https://github.com/Adam-yni/LLM-reasoning-finetuning): Repository for end-to-end fine-tuning of a Large Language Model (LLM), featuring high-quality data generation using Monte Carlo Tree Search. The generated data consists of annotated mathematical reasoning steps, each assigned a continuous value between 0 and 1 representing the probability that the step leads to the correct result. The repository includes: Code to fine-tune an LLM on the generated dataset to create a Process Reward Model (PRM) / Code to fine-tune an LLM using reinforcement learning, specifically with Proximal Policy Optimization (PPO), with a stable implementation **(20% relative improvement on math HARD)** / Code for guided search, where at each step of a mathematical reasoning process, the LLM proposes multiple possible steps. The PRM selects the most promising step, which is then added to the reasoning process, iterating until the final result is reached. **This approach has demonstrated a 20% absolute improvement on one of the most challenging mathematical benchmarks** (Math HARD) for reasoning processes involving a sufficiently large number of steps (8 steps).

- [GflowNets FineTuning](https://github.com/Adam-yni/GFlowNets-FineTuning): This repository contains the code to **fine-tune a Large Language Model (LLM) using GFlowNets**, a novel reinforcement learning-inspired approach for training LLMs. **It is one of the first publicly available implementations for fine-tuning an LLM with GFlowNets.**
- [GPoeT](https://github.com/Adam-yni/GPoeT): A personal project to create a **tiny language model (LLM) for generating poetry in French**. The model contains 40M parameters and was entirely trained on a Kaggle notebook (free tier with an NVIDIA P100 GPU, 16GB VRAM).
- [Causal Survival Estimators](https://github.com/Adam-yni/Causal-survival-estimators): This repository contains a **modification of a classical non-parametric estimator in survival analysis: the Kaplan-Meier estimator**. The aim is to make this estimator less biased using causal quantities such as the propensity score.
- [Kaggle ML](https://github.com/Adam-yni/kaggle_machine_learning): Code used for a Kaggle competition, where the model developed with this code **ranked in the top 5-6 out of 80 teams**.

- [SCIGAN](https://github.com/Adam-yni/Causal-Inference-CounterFactual-World): This repository contains an implementation of the code proposed in the article titled: [Estimating the Effects of Continuous-valued Interventions using Generative Adversarial Networks](https://arxiv.org/abs/2002.12326). The original code, written in TensorFlow, has been converted to PyTorch. Some structural modifications were necessary, but the results obtained on the TCG dataset are consistent with the original results.

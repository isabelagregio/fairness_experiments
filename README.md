# LLM Fairness & Safety — Research Experiments

Undergraduate research conducted at the **Itaú Data Science Center**, supervised by Prof. Artur Jordão, investigating fairness, robustness, and safety in open-source Large Language Models (LLMs).

## Research & Contributions

- **Fairness & Bias Mitigation:** Developed a testing-time adversarial approach using prompt variations to detect and reduce racial bias in LLM predictions.
- **LLM Fine-Tuning:** Explored supervised fine-tuning and refusal-training techniques to improve model safety.
- **Adversarial Evaluation:** Conducted experiments involving harmful prompts, prompt injection, and robustness assessment across open-source LLMs.
- **Experimental Analysis:** Evaluated model behavior and fairness metrics across different configurations.

## Published Research

**[Improving Fairness in LLMs Through Testing-Time Adversaries](https://arxiv.org/abs/2505.12100)** — Gregio et al., 2025.

The proposed inference-time method improved fairness metrics on Llama 3 by up to **27 percentage points**, without additional training or parameter updates.

## Repository Structure

- `harmful_experiment/` — Harmful-content evaluation and data augmentation.
- `harmful_experiment_finetuning/` — Fine-tuning experiments for model safety.
- `prompt_injection/` — Prompt-injection experiments and evaluation.
- `interpreter/` — Supporting experimental utilities.

**Tech Stack:** Python · PyTorch · Hugging Face Transformers · Llama · LLM Fine-Tuning · Adversarial Testing

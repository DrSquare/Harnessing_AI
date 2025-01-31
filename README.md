# AI Coding & LLM Prompt Engineering

## Introduction
This repository provides resources and demos related to AI-assisted coding, autoregressive large language models (LLMs), and advanced prompt engineering techniques.

### Topics Covered:
1. AI-Assisted Coding
2. Autoregressive Large Language Models (LLMs)
3. Prompt Engineering 201

---

## AI-Assisted Coding
The repository contains a **Jupyter Notebook** (`AI_ASSISTED_CODING.ipynb`) demonstrating AI-assisted coding techniques using language models.

---

## Autoregressive Language Models
Autoregressive LLMs predict the next word based on input text and operate as probability kernels.

### Key Concepts:
- **Next-Word Prediction:** Given a prefix, the model generates the most likely next word.
- **Stochastic Nature:** A given input may produce different outputs sampled from probability distributions, which can result in inconsistencies or hallucinations.
- **Probability Calculations:** Language models assign probabilities to sequences of words based on prior observations.

### Types of Large Language Models:
1. **Base LLM (Pre-Trained):** Trained on large text corpora to predict the next word in a sentence.
2. **Instruction-Tuned LLM (Fine-Tuned):** Optimized to follow instructions and improve response accuracy using techniques such as:
   - Supervised Fine-Tuning (SFT)
   - Reinforcement Learning with Human Feedback (RLHF)
   - Direct Preference Optimization (DPO)

---

## Sampling and Parameters
### Key Parameters Controlling Model Outputs:
- **Temperature:** Controls randomness (higher values = more creativity, lower values = more deterministic responses).
- **Top-p (Nucleus Sampling):** Limits token selection to the most probable subset.
- **LogProbs:** Logs probability scores for debugging and confidence analysis.
- **Penalties:**
  - **Frequency Penalty:** Reduces repetition of frequent words.
  - **Presence Penalty:** Encourages diverse outputs by avoiding repeated phrases.
- **Max Tokens:** Limits response length.
- **Stop Sequences:** Defines token sequences that halt text generation.
- **n & best_of:** Controls the number of completions generated.

---

## Prompt Engineering 201
The repository includes a **Jupyter Notebook** (`PROMPT_ENGINEERING.ipynb`) demonstrating prompt optimization techniques for LLMs.

### Core Topics:
- **Understanding Model Behavior:** Fine-tuning prompts to achieve desired responses.
- **Controlling Creativity & Accuracy:** Adjusting parameters for structured, coherent, and relevant outputs.
- **Debugging Model Responses:** Using log probabilities to refine prompts.

---

## Demo & Usage
To explore the concepts, run the provided Jupyter Notebooks:
1. `AI_ASSISTED_CODING.ipynb` – AI-assisted coding demonstrations.
2. `PROMPT_ENGINEERING.ipynb` – Advanced prompt engineering strategies.

---

## References
- DeepLearning.AI – ChatGPT Prompt Engineering
- Stanford NLP (CS224N)
- AI Engineering Research

For contributions, open a pull request or create an issue in this repository. Happy coding!


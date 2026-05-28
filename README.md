# 🧠 Prompt Engineering Explorer

> A hands-on notebook for mastering prompt engineering techniques with LLMs — from zero-shot basics to advanced in-context learning.

---

## 📌 Overview

This project is a practical, beginner-friendly guide to **prompt engineering** — the art of crafting effective instructions for Large Language Models (LLMs). Using **LangChain** , this notebook walks you through foundational and advanced techniques, and shows how to apply them in real-world NLP applications.

Whether you're just getting started with LLMs or looking to sharpen your prompting skills, this repo has something for you.

---

## 🚀 What You'll Learn

- ✅ How to write effective prompts that communicate clearly with LLMs
- ✅ Zero-shot, one-shot, and few-shot prompting
- ✅ Chain-of-Thought (CoT) prompting
- ✅ Self-consistency techniques
- ✅ Using LangChain's `PromptTemplate` and `LLMChain`
- ✅ Building practical LLM-powered applications

---

## 🛠️ Techniques Covered

| Technique | Description |
|---|---|
| **Zero-shot prompting** | Ask the model without any examples |
| **One-shot prompting** | Provide a single example to guide the model |
| **Few-shot prompting** | Use multiple examples for better accuracy |
| **Chain-of-Thought (CoT)** | Encourage step-by-step reasoning |
| **Self-consistency** | Sample multiple outputs and select the best |

---

## 📦 Applications Built

- 💬 **QA Bot** — Answer questions from a given context
- 📝 **Text Summarization** — Condense long content into key points
- 🏷️ **Text Classification** — Categorize text into predefined labels
- 💻 **Code Generation** — Generate code snippets from natural language
- 🎭 **Role-playing Agent** — Give the model a persona (e.g., Game Master)

---

## 📂 Project Structure

```
prompt-engineering-explorer/
│
├── prompt-engineering-v1.ipynb   # Main notebook with all techniques & applications
└── README.md
```


## 🧪 Exercises Included

The notebook includes 3 hands-on exercises to test your understanding:

1. **Change LLM parameters** — Experiment with `temperature`, `top_p`, `max_new_tokens`
2. **Observe how the LLM thinks** — Enable `verbose=True` to see the model's reasoning
3. **Revise to one-shot learning** — Upgrade a zero-shot classifier to one-shot

---

## 🏃 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/prompt-engineering-explorer.git
   cd prompt-engineering-explorer
   ```

2. Install the required libraries (see above)

3. Set up your IBM watsonx.ai credentials

4. Open and run the notebook:
   ```bash
   jupyter notebook prompt-engineering-v1.ipynb
   ```

---

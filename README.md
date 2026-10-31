# 🤖 Machine Learning to Agentic AI

> Hands-on notebooks that follow the path from classic machine learning to modern Generative AI: prompt engineering, vector embeddings and Retrieval-Augmented Generation (RAG), the building blocks of AI agents.

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)
![Groq](https://img.shields.io/badge/LLM-Groq%20API-F55036)
![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)

## 📌 Overview

AI is moving from **perception** (models that recognise images, text and speech) to **autonomy** (agents that reason, retrieve information and take actions). This repository is a practical learning track for that shift. Each notebook covers one core skill needed to build LLM applications and AI agents, with runnable code.

## 🗺️ Learning path

```mermaid
flowchart LR
    A[📊 Machine Learning<br/>Perception] --> B[✍️ Prompt Engineering<br/>Talking to LLMs]
    B --> C[🔢 Vectors & Embeddings<br/>Meaning as numbers]
    C --> D[📚 RAG<br/>Grounding LLMs in<br/>your own data]
    D --> E[🤖 Agentic AI<br/>Reasoning + tools<br/>+ actions]
```

## 🏗️ How the RAG pipeline works

```mermaid
flowchart TD
    Q[❓ User question] --> R[🔎 Retrieve relevant<br/>context from the<br/>knowledge base]
    K[(📚 Knowledge base)] --> R
    R --> P[🧩 Build prompt:<br/>question + context]
    P --> L[🧠 LLM via Groq API]
    L --> A[✅ Answer grounded<br/>in the retrieved facts]
```

## 📒 Notebooks

| Notebook | Topic | What you learn |
|---|---|---|
| `Prompts_LLM/` | Prompt engineering | Writing clear, effective prompts for large language models |
| `Vector_and_Embedding.ipynb` | Embeddings and similarity | Representing text as vectors and comparing them with cosine similarity (applied to sentiment analysis) |
| `RAG_Day_1.ipynb` | Retrieval-Augmented Generation | Supplying an LLM with an external knowledge source so it answers from authoritative data instead of only its training data |

## 🧰 Tech stack

Python · Jupyter / Google Colab · Groq LLM API · NumPy · scikit-learn

## ⚙️ Getting started

```bash
git clone https://github.com/SaurabhSharma2388/Machine-Learning-to-Agentic-AI.git
cd Machine-Learning-to-Agentic-AI
pip install groq numpy scikit-learn jupyter
export GROQ_API_KEY="your_key"
jupyter notebook
```

Each notebook also has an **Open in Colab** link.

## 🔭 Coming next

- Vector databases (FAISS, Chroma) for semantic search at scale
- Tool calling and multi-step AI agents
- Evaluating RAG quality (faithfulness and context accuracy)

## 👤 Author

**Saurabh Sharma** – Senior Data Scientist & Generative AI Engineer
[LinkedIn](https://www.linkedin.com/in/saurabh-sharma-data-scientist/) · [GitHub](https://github.com/SaurabhSharma2388)

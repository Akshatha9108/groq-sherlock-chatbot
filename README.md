The Adventures of Sherlock Holmes (PDF):
https://archive.org/download/adventuresofsher00doylrich/adventuresofsher00doylrich.pdf
# groq-sherlock-chatbot

# 🕵️‍♂️ Sherlock Holmes Document-Aware Chatbot (Groq AI Powered)

A Generative AI chatbot that interacts with a 300+ page Sherlock Holmes novel to answer user questions in context, powered by Groq’s ultra-fast LLM inference.

## 📘 Document Used
- **Title**: The Adventures of Sherlock Holmes
- **Author**: Arthur Conan Doyle
- **Link**: [Download PDF](https://archive.org/download/adventuresofsher00doylrich/adventuresofsher00doylrich.pdf)

## 🧠 Features
- Ingests and processes long documents
- Uses vector search with FAISS + HuggingFace Embeddings
- Sends relevant chunks and user queries to Groq AI
- Provides contextual and smart answers
- Handles vague questions and fallback logic

## 🛠️ Tech Stack
- Groq API (`meta-llama/llama-4-scout-17b-16e-instruct`)
- LangChain
- FAISS
- HuggingFace Sentence Transformers
- PDFMiner
- Google Colab

## 🧪 Sample Questions
```plaintext
🔎 How does Sherlock Holmes solve "The Red-Headed League"?
🔎 Who is Dr. Watson and what is his role?
🔎 Explain Holmes' method of deduction in simple terms.
```

## 💻 How to Run
Open the Colab Notebook

Upload the PDF or use the existing one

Paste your Groq API key when prompted

Ask your question!

## 🧰 Requirements
pip install langchain faiss-cpu sentence-transformers pdfminer.six requests

##🔐 Get Groq API Key
- Go to https://console.groq.com

- Click on API Keys > Generate Key

- Use it in the notebook like:

import os
os.environ["GROQ_API_KEY"] = "your_api_key_here"

### Visit Groq Cloud and create your free API key.

---

### 🔗 3. Include Google Colab Link

Inside your README, add:

```markdown
▶️ [Run on Google Colab]
https://colab.research.google.com/drive/1HQB9J3N7kyhR4x0X91wT9RlgnExzf8kZ?usp=sharing

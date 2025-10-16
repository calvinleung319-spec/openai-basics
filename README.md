# openai-basics

Hands-on Python projects demonstrating core **OpenAI API** functionalities — chat completion, summarization, and embeddings — forming the foundation for **Retrieval-Augmented Generation (RAG)** and **LLM-powered** applications.

---
## Overview

This repository provides practical, minimal examples to help you understand how OpenAI’s models can be used in real-world workflows.
Each script covers a key concept that’s fundamental to GenAI development:

| Script              | Description                                     | Key Concepts                                |
| ------------------- | ----------------------------------------------- | ------------------------------------------- |
| `simple_chat.py`    | Interactive chatbot using gpt-5/gpt-5-mini      | ChatCompletion API, system prompts          |
| `summarize_text.py` | Summarizes long text into concise points        | Prompt engineering, summarization           |
| `embedding_demo.py` | Creates embeddings and performs semantic search | Vector embeddings, FAISS, similarity search |


## Features

- Uses the **OpenAI API (gpt-5 / gpt-5-mini)** for natural language tasks
- Demonstrates **prompt design** and **context handling**
- Builds **semantic search** foundation for RAG pipelines
- Easily extendable for LangChain, Streamlit, or Flask integration
- Cloud-ready structure (can deploy on Azure, AWS, or GCP)

---
## Setup Instructions
### 1. Clone the repository
```
git clone https://github.com/<your-username>/openai-basics.git
cd openai-basics
```

### 2. Install dependencies
```
pip install openai python-dotenv faiss-cpu
```

### 3. Set up your environment
Create a `.env` file in the project root with your OpenAI API key:
```
OPENAI_API_KEY=sk-yourkeyhere
```

### 4. Run any script
```
python simple_chat.py
python summarize_text.py
python embedding_demo.py
```

---
## Example Output
### Chatbot
```
You: What is insurance underwriting?
AI: Insurance underwriting is the process of evaluating risk and determining appropriate premiums.
```

### Summarization
```
Input: long paragraph →
Output: “Insurance transfers financial risk by providing protection against unforeseen losses.”
```

### Embedding Search
```
Query: What does car insurance cover?
Top Match: "Car insurance covers damage or loss to vehicles."
```

---
## Tech Stack

- **Language:** Python 3.10+
- **Libraries:** OpenAI, FAISS, python-dotenv
- **Models:** `gpt-5-mini`, `text-embedding-3-small`
- **Environment:** Local / Cloud compatible (Azure / GCP / AWS)

---

## Next Steps / Extensions

If you want to build on this repo:

- Combine `embedding_demo.py` + `simple_chat.py` into a **RAG chatbot**
- Add a **Streamlit UI** for user interaction
- Deploy on **Azure App Service** or **Docker container**
- Add evaluation via **LangSmith** or **TruLens**

---

## Author

**Calvin Leung**  
🔹 Data & AI Enthusiast | LLM Developer | Python / LangChain / Azure  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/calvinleung319)

---

## License

This project is open-source under the MIT License.




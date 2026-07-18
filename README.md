# QI_AGENT 🤖📄

QI_AGENT is an intelligent, agentic Research Intelligence System designed to automate literature search, exploration, and synthesis. Powered by **LangGraph** and **LangChain**, the agent dynamically decides when to query a vector database, extract top-tier keyphrases, or construct tabular comparisons between complex machine learning manuscripts.

---

## 🚀 Key Features

*   **Semantic Literature Search:** Indexes and queries 15,000+ Machine Learning ArXiv papers using `SentenceTransformers` (`all-MiniLM-L6-v2`) and a normalized `FAISS` vector database.
*   **Deep Abstract Summarization:** Leverages the `facebook/bart-large-cnn` pipeline to provide concise, factual paper breakdowns.
*   **Keyphrase Extraction:** Integrates `KeyBERT` for identifying high-relevance domain concepts and keywords without manual prompt tuning.
*   **Comparative Analysis:** Auto-generates structured, granular comparison tables (Objectives, Methodologies, Limitations, Applications) between multiple research directions using `Llama-3.1-8b-instant`.
*   **ReAct Agent Architecture:** Utilizes LangGraph's stateful runtime loops to robustly route text instructions to specialized algorithmic toolchains.

---

## 🛠️ Tech Stack

*   **Orchestration / Architecture:** LangGraph, LangChain[cite: 1]
*   **LLM Provider:** Groq Cloud API (`Llama-3.1-8b-instant`)[cite: 1]
*   **Vector Engine & Embeddings:** FAISS (IndexFlatIP), Hugging Face Sentence Transformers[cite: 1]
*   **NLP Processing Hub:** KeyBERT, Transformers (BART)[cite: 1]
*   **Data Handling:** Pandas, NumPy, Hugging Face Datasets[cite: 1]

---

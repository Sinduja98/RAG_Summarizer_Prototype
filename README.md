
**AI-Driven Medical Assistant**

A Medical Records Summarization Chatbot that retrieves relevant medical records from a collection and generates concise summaries using Sentence-BERT for document embedding, FAISS for efficient document retrieval, and OpenAI GPT-3.5 (or GPT-4) for summarization.

Features:
- Search: The system uses Sentence-BERT embeddings and FAISS to search for the most relevant medical records based on a user's query.
- Summarization: The relevant medical records are summarized using OpenAI's GPT model.
- Gradio Interface: A user-friendly Gradio interface for easy interaction with the system.

Prerequisites:
- Python 3.x
- Google Colab (optional for secret management)
- OpenAI API Key (for GPT-based summarization)

Setup & Installation:
- Clone the repository
   - git clone (https://github.com/Sinduja98/RAG_Summarizer_Prototype.git)
   - cd RAG_Summarizer_Prototype
- You should install the necessary libraries for your Jupyter notebook
   - openai
   - sentence-transformers
   - faiss-cpu
   - numpy
   - gradio


# Chat_with_pdf


Hi folks,

- **Introduction to Chat_with_pdf:**
  - This repository contains a hands-on project to explore chatting with any PDF.
  - An LLM trained on a large corpus may not always be able to answer your query efficiently. Hence, providing context in the prompt becomes important.
  - Here we use RAG methodology where we store our PDFs in a vector database (used Pinecone) in the form of embeddings.
  - Whenever we provide a query, we retrieve the closest (similar or relevant) chunk embeddings and provide them as context in the prompt to any large language model, preventing LLM from hallucinating and giving outdated responses.


# Chat_with_pdf


Hi folks,
This repository contains a hands-on project to explore chatting with any pdf.\\
An LLM trained on a large corpus may not always be able to answer your query efficiently.Hence,providing context in the prompt becomes important.\\
Here we use RAG methodology where we store our pdf in a vector database(used pinecone) in the form of embeddings.\\
Whenever we provide a wuery,we retrieve the closest(similar or relevant) chunk embeddings and provide it as a context in th eprompt to any large language model which prevents LLM from hallucinating and giving outdated response\\

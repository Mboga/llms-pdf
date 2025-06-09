# llms-pdf
testing the docling library. I will use the langGraph and langChain libraries
- Use Docling to extract and prepare the dcoument data
- Use Milvus to store and retrieve embeddings: scalable, high-performance RAG application

# Domain: document processing
The objective is to build a knowledge graph using locally stored pdfs. This use-case can be extended to different kind of documents in a business

# Workflow
- Data Preparation: Extract text from PDFs using Docling
- Embedding and Vector Database: Convert text to embeddings, and store them for retrieval
- RAG pipeline: Build the RAG using LangChain
- Lightweight LLM: Use a Hugging Face Modelthat runs efficiently on your hardware
- Jupyter notebook: For interactivity
- Document Classification and Clustering using embeddings database
- Cacheing of conversations: memory to chats and conversations

# set up environment


Create a python virtual environment 

``` python3 -m venv llm_pdf```

Activate the environment 

``` source llm_pdf/bin/activate```
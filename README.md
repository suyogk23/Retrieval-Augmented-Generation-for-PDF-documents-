
# Retrieval Augmented Generation for PDF documents 

A simplified RAG system which generates context specific responses using LLMs(Llama3.1). Built using llama3.1, LangChain and HuggingFace_embeddings.


Why RAG?

Retrieval Augmented Generation (RAG) enhances AI models by combining retrieval and generation. It ensures accurate and up-to-date responses by dynamically accessing external sources, reducing hallucinations, and personalizing answers. This approach is scalable, cost-effective, and offers explainability by tracing responses back to specific sources.

## Implementation Overview
Divided the documents into smaller chunks. Embedded the documents with embedding model. Store them in a vector store from which retriever fetches the relevant documents accourding the to users's query. These documents are then fed to the LLM along with the query in a prompt template. 

Used "LLama3.1 (8B parameters)" as LLM. Used "BAAI/bge-base-en-v1.5" as embedding model. 







## Installation

Create a python virtual environment(optional). Run the notebook.

```bash
  python3 -m venv .<your_env_name>
  source .<your_env_name>/bin/activate
```
    
##References 
https://www.youtube.com/@underfitted# Retrieval-Augmented-Generation-for-PDF-documents-

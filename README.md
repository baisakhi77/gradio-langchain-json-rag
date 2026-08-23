# gradio-langchain-json-rag
 An interactive RAG-powered Q&amp;A application built with Gradio and LangChain, enabling users to query custom JSON datasets using semantic search

## Description

A full-stack Retrieval-Augmented Generation (RAG) application built with Gradio, ChromaDB, and Llama 3. This system allows users to upload custom JSON datasets, persist embeddings locally in a vector database, and query the data through an interactive chat interface with source-aware context retrieval.

## Dataset

https://github.com/RUCAIBox/HaluEval/blob/main/data/qa_data.json

## Getting Started

## Installation Steps

### The required Python libraries

* pip install gradio==4.44.0
* pip install --upgrade gradio
* pip install ibm-watsonx-ai==1.1.2
* pip install langchain==0.2.11
* pip install langchain-community==0.2.10
* pip install langchain-ibm==0.1.11
* pip install chromadb==0.4.24
* pip install pypdf==4.3.1
* pip install pydantic==2.9.1
* pip install huggingface_hub==0.23.0
* pip install gradio
* pip install huggingface_hub
* pip install --upgrade chromadb
* pip install openai
* pip install sentence-transformers
* pip install jq
* pip install "transformers<4.49.0"
* pip install --force-reinstall numpy==1.26.4

### LLM installation
!sudo apt-get update && sudo apt-get install -y zstd
!curl -fsSL https://ollama.com/install.sh | sh

### Executing program

* Execute Chatbot.ipynb after installing the required Python library and starting Ollama.

## Result

<img width="1508" height="398" alt="image" src="https://github.com/user-attachments/assets/3139edbf-d730-454f-a4b2-b1e0fc5ff567" />


## Authors

Contributors names and contact info

Baisakhi Mitra (baisakhi7.mitra7@gmail.com)


## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments


# gradio-langchain-json-rag
 An interactive RAG-powered Q&amp;A application built with Gradio and LangChain, enabling users to query custom JSON datasets using semantic search

## Overview

A full-stack Retrieval-Augmented Generation (RAG) application built with Gradio, ChromaDB, and Llama 3. This system allows users to upload custom JSON datasets, persist embeddings locally in a vector database, and query the data through an interactive chat interface with source-aware context retrieval.


## Datasets

We use the [HaluEval](https://github.com/RUCAIBox/HaluEval) benchmark for testing and evaluating model hallucinations. 

<Quote bind="1.1.9">HaluEval is a large collection of generated and human-annotated hallucinated samples for evaluating the performance of LLMs in recognizing hallucination, as introduced in [HaluEval](https://github.com/RUCAIBox/HaluEval).</Quote>

## Python packages used
* langchain
* langchain_community
* gradio
* langchain_core

## Running the Notebook

Click the **Open in Colab** badge above to launch and execute this Jupyter notebook directly in your browser via [Google Colab](https://drive.google.com/file/d/1HksFGSMJZVsSyoSdYYYjo90QAmGp4Flv/view?usp=sharing). No local installation is required.

### Steps:
1. Click the **Open In Colab** button.
2. Once the notebook opens in Google Colab, you can run individual code cells by clicking the **Play button** or pressing `Shift + Enter`.
3. If your notebook requires a GPU (for machine learning or AI models), go to **Runtime** > **Change runtime type** in the top menu and select **T4 GPU** (or another available accelerator), then click **Save**.

## Usage
1. Upload the JSON file mentioned in the Dataset section.
2. Click on 'Process JSON'.
3. Chat with the qabot by entering a question in 'Input Query' section and getting the answer in 'Output' box.
<img width="1508" height="398" alt="image" src="https://github.com/user-attachments/assets/3139edbf-d730-454f-a4b2-b1e0fc5ff567" />


### Citation

@misc{HaluEval,
  author = {Junyi Li and Xiaoxue Cheng and Wayne Xin Zhao and Jian-Yun Nie and Ji-Rong Wen },
  title = {HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models},
  year = {2023},
  journal={arXiv preprint arXiv:2305.11747},
  url={https://arxiv.org/abs/2305.11747}
}
### Acknowledgments

* AI model inference powered locally by [Ollama](https://ollama.com/).
* This project uses the following open-source libraries:
  * [LangChain](https://github.com/langchain-ai/langchain) (`langchain`, `langchain_core`, `langchain_community`)
  * Gradio](https://github.com/gradio-app/gradio) - UI framework for building machine learning demos.


## Contact

Contributors names and contact info

Baisakhi Mitra (baisakhi7.mitra7@gmail.com)




# Llama 2 with LlamaIndex

This project integrates Llama 2, a state-of-the-art large language model, with LlamaIndex (formerly GPT Index) to perform natural language processing tasks such as document embedding and querying.

## Project Overview

The notebook demonstrates:
- Setting up and using the Llama 2 model.
- Integrating the model with LlamaIndex for text embeddings.
- Processing and embedding documents, such as PDFs, with AI-driven insights.

## Prerequisites

To run this notebook, you need the following:
- Python 3.8+
- Jupyter Notebook or Jupyter Lab

### Required Python Libraries

You can install the required libraries using the following commands:

```bash
pip install transformers einops accelerate langchain bitsandbytes
pip install sentence-transformers
pip install llama-index pypdf
```

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/Sujgaik2003/Llama2_with_LlamaIndex.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Llama2_with_LlamaIndex
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook Llama2_with_llamaindex.ipynb
    ```
5. Follow the steps in the notebook to explore the integration of Llama 2 with LlamaIndex.

## Usage

- Load and prepare the Llama 2 model for NLP tasks.
- Use the notebook to process input documents (e.g., PDFs) and analyze them using LlamaIndex.
- Perform text embeddings with `sentence-transformers`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Llama 2](https://github.com/facebookresearch/llama) by Meta AI.
- [LlamaIndex](https://github.com/jerryjliu/llama_index) for data management with LLMs.
- [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) for text embeddings.

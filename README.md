# LLM Playground

## Purpose

The **LLM Playground** repository is a sandbox for experimenting with Hugging Face's transformers and other tools within the AI/ML ecosystem. This project focuses on working with large language models (LLMs), integrating them into practical applications, and exploring various techniques for natural language processing (NLP) and deep learning. The primary backend is PyTorch, with GPU acceleration via CUDA 11.8 on an NVIDIA RTX 2070.

## Key Features

- **Experimentation with Hugging Face Transformers**:
  - Running, fine-tuning, and deploying large language models (LLMs).
  - Supporting both **online** and **offline modes**, depending on privacy and resource requirements.
- **PyTorch Integration**:
  - Using PyTorch for custom model development, training, and deployment.
  - Leveraging GPU acceleration with CUDA 11.8.
- **Exploration of Hugging Face Ecosystem**:
  - **Transformers**: Pre-trained models for NLP tasks such as text generation, classification, translation, and summarization.
  - **Datasets**: Access to a large collection of datasets for training, fine-tuning, and evaluation.
  - **Tokenizers**: Efficient tokenization of text for feeding into models.
  - **Hugging Face Hub**: Utilizing the hub for hosting, sharing, and discovering models, datasets, and pipelines.
  - **Inference API**: Testing models directly without local installation.
- **Data Handling and Preprocessing**:
  - Working with datasets to build and evaluate models for practical applications.
  - Exploring different data formats and preprocessing pipelines for NLP tasks.

## Repository Structure

- **projects**: Parent directory containing individual project folders, each with its own structure for managing experiments and workflows.

  - **notebooks**: Jupyter notebooks containing experiments and tutorials on various LLM and NLP workflows for the specific project.
  
  - **data**: A folder (excluded from Git) for storing raw and processed datasets related to the project.
  
  - **scripts**: Python scripts for automating tasks such as data preprocessing, model training, and evaluation specific to the project.
  
  - **documentation**: Research notes, guides, and documentation about the experiments and workflows within the project.


## Usage

1. Clone the repository and navigate into the project directory:

   ```bash
   git clone https://github.com/sewald101/llm_playground.git
   cd llm_playground
2. Set up and activate a Conda virtual environment:

   ```bash
   conda env create -f environment.yml
   conda activate llm_playground
## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/licenses/MIT) file for details.


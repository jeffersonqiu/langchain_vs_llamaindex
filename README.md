# LangChain vs Llama-index: A Comparison for RAG Applications

Welcome to the repository comparing LangChain and Llama-index frameworks for Retrieval-Augmented Generation (RAG) purposes. This repo contains Jupyter notebooks demonstrating how to build LLM RAG systems using both frameworks.

## Table of Contents
- [Introduction](#introduction)
- [Motivation](#motivation)
- [Similarities](#similarities)
- [Framework-Specific Advantages](#framework-specific-advantages)
  - [Llama-index](#llama-index)
  - [LangChain](#langchain)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Retrieval-Augmented Generation (RAG) is an approach that combines the power of retrieval systems with the generative capabilities of large language models (LLMs). This repository provides a side-by-side comparison of two popular frameworks used for building RAG systems: LangChain and Llama-index.

## Motivation
While both LangChain and Llama-index are widely used and well-documented, there is a lack of clear guidance on their differences, similarities, and which one might be more suitable for beginners. This repository aims to fill that gap.

## Similarities
Both frameworks are:
- Easy to use
- Well-documented
- Comprehensive in their integration with external APIs (data structures, vector stores, LLMs)

## Framework-Specific Advantages

### Llama-index
- **Better data chunking ability**: Maintains node relations (node.next, node.previous) for better context retention.
- **More precise control**: Offers detailed control over vector store and indexing.
- **Higher level of abstraction**: Skips many steps required in LangChain, such as retrieval and prompt declaration.

### LangChain
- **Easy and readable pipelining**: Simplifies workflows through LCEL.
- **Integration with LangServer**: Facilitates [specific features or capabilities].
- **LangSmith integration**: Eases troubleshooting processes.

## Usage
To explore the differences between LangChain and Llama-index, you can run the provided Jupyter notebooks:

1. **LangChain_RAG.ipynb**: Demonstrates the use of LangChain for building an RAG system.
2. **Llama_index_RAG.ipynb**: Shows how to build an RAG system using Llama-index.

## Installation
To run these notebooks, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/jeffersonqiu/langchain_vs_llamaindex
   cd RAG-comparison

2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
  source env/bin/activate  # On Windows, use `env\Scripts\activate`

3. Install the required packages:
   ```bash
   pip install -r requirements.txt

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook

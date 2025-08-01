# RAG-LLM Pipeline for Extracting and Generating Insights from PDF/XML File

<a href="https://colab.research.google.com/github/semanticClimate/RAG-LLM-with-PDF-XML/blob/main/FSCI2025_RAG_LLM_PDF.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" style="max-width: 100%;">
</a>

DOI Zenodo badge: 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16675979.svg)](https://doi.org/10.5281/zenodo.16675979)

Citation:

Barbhuiya, S., Alwi, K. K., Kumari, R., S., A., Jawed, M., Simon, W., Yadav, G., & Murray-Rust, P. (2025). RAG-LLM Pipeline for Extracting and Generating Insights from PDF/XML File (0.2). Zenodo. https://doi.org/10.5281/zenodo.16675979

Description: 

This notebook demonstrates how to build a semantic question-answering system over scientific PDFs using Retrieval-Augmented Generation (RAG) and Large Language Models (LLMs). It enables users to upload PDFs, extract content, embed it into a vector store, and query the document using natural language.

**Key Features**
- PDF Upload & Text Extraction: Extract raw text from research papers using PyMuPDF
- Text Chunking & Embeddings: Convert text into meaningful chunks and generate embeddings using models like sentence-transformers
- RAG Pipeline:
    - Store document chunks in a FAISS vector database
    - Retrieve top-matching chunks based on user queries
    - Generate context-aware answers with an LLM
    - Natural Language Q&A: Ask questions like “What is the main finding?” or “What methods were used?” and get accurate answers drawn directly from the paper

[Link to Notebook](https://colab.research.google.com/drive/17J9wEvkQvdaeOihN3N13u_ln5Oez8ssd?usp=sharing)

Reviewers & review process: \<Add reviewers and review process link\> 

---

Software citation information: [CITATION.cff](CITATION.cff)

License: Apache License Version 2.0, January 2004 http://www.apache.org/licenses/ | License information: [LICENSE](LICENSE)

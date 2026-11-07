# Luxembourg IMF Financial Stability Analysis Using LLMs

## Project Overview
This project analyses Luxembourg's 2023 IMF Article IV Consultation Report (Country Report No. 23/176) using Large Language Models (LLMs). The aim is to extract financial indicators, summarise economic developments, identify financial stability risks and present the findings through an interactive analysis pipeline and visual dashboard.

## Models Used
- **SmolLM3-3B:** Main model for summarisation, financial extraction and RAG answer generation.
- **Qwen3-1.7B:** Independent LLM-as-a-Judge for evaluating accuracy, completeness and consistency.
- **BAAI/bge-small-en-v1.5:** Embedding model for semantic retrieval using FAISS.

## Main Features
- PDF text extraction and token-aware chunking.
- Executive summary and seven section summaries.
- Structured financial indicator extraction in JSON.
- Analysis of seven financial stability themes.
- Identification of economic strengths and vulnerabilities.
- FAISS-based Retrieval-Augmented Generation (RAG).
- Automated LLM evaluation and source verification.
- High-resolution four-panel financial dashboard.

## How to Run
1. Open the Luxembourg project notebook in Google Colab.
2. Enable a GPU (A100 recommended; T4 supported).
3. Upload the Luxembourg IMF PDF when prompted.
4. Run all notebook cells sequentially.
5. Review the generated JSON files, evaluation results and dashboard.

## Dataset
**Source:** International Monetary Fund (2023). *Luxembourg: 2023 Article IV Consultation—Press Release; Staff Report; and Statement by the Executive Director for Luxembourg*. IMF Country Report No. 23/176.

## Tools and Libraries
Python, Google Colab, PyMuPDF, Hugging Face Transformers, Sentence Transformers, FAISS, Pandas, NumPy and Matplotlib.



## Academic Purpose
Developed for the Data Analysis with AI – LLM coursework to demonstrate financial document processing, structured extraction, semantic retrieval, model evaluation and economic visualisation.

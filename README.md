# Local RAG System for PDF Text Preprocessing and Embedding

## Description

This project implements a local RAG (Retrieval-Augmented Generation) system designed to preprocess text data from PDF files, embed the processed text into vector representations, and enable vector-based search. The system is intended to provide relevant contextual information to an LLM (Large Language Model) by retrieving and incorporating the most pertinent sections of the PDF into the model's input.

## Dependencies

- `fitz` (PyMuPDF) for PDF reading and processing.
- `pandas` for data manipulation and analysis.
- `spacy` for sentence segmentation.
- `tqdm` for progress tracking in loops.
- `random` for random operations.
- `torch` for tensor operations.
- `numpy` for numerical operations.
- `sentence_transformers` for sentence embeddings.
- `transformers` for model loading and processing.

## Examples

The notebook provides examples of how to:

- Read and preprocess text from a PDF file.
- Split the text into sentences using SpaCy.
- Organize the text into chunks for embedding.
- Calculate statistics on page content, such as word and sentence counts.

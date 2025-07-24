# MedSummRAG
This repository contains the code for our BioNLP 2025 paper:
"MedSummRAG: Retrieval-Augmented Generation for Medical Text Summarization".

## Overview
MedSummRAG is a retrieval-augmented generation (RAG) framework designed to improve medical text summarization. It integrates external domain-specific knowledge by:

Using a fine-tuned dense retriever trained with contrastive learning

Retrieving relevant medical documents

Feeding both the input and retrieved documents to a language model to generate better summaries

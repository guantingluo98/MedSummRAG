# MedSummRAG
This repository contains the code for our BioNLP 2025 paper:
"MedSummRAG: Retrieval-Augmented Generation for Medical Summarization".

## Overview
MedSummRAG is a retrieval-augmented generation (RAG) framework designed to improve medical text summarization. It integrates external domain-specific knowledge by:

Using a fine-tuned dense retriever trained with contrastive learning

Retrieving relevant medical documents

Feeding both the input and retrieved documents to a language model to generate better summaries

## Data preparing
1. CHQ-Summ Dataset (Medical QA Summarization)
We use the CHQ-Summ dataset from Shweta et al., which contains community health questions and reference summaries.
https://github.com/shwetanlp/Yahoo-CHQ-Summ
2. External Knowledge Base (Yahoo! Answers L6)
To support retrieval-augmented generation, we use the Yahoo! Answers L6 dataset as our external medical knowledge base.
https://webscope.sandbox.yahoo.com/catalog.php?datatype=l&did=11

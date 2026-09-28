# Exploratory Data Analysis and Visualization of Credit Card Fraud Data

## Overview

This project presents an Exploratory Data Analysis (EDA) and visualization workflow performed on a credit card transaction dataset.

The objective of the analysis is to understand the structure and characteristics of the transaction data, identify data-quality issues, examine the distribution of variables, investigate potential outliers, and explore patterns associated with fraudulent and legitimate transactions.

The analysis was implemented in Python using a Jupyter Notebook and includes data cleaning, statistical exploration, outlier analysis, and multiple visualizations designed to communicate important patterns in the dataset.

---

## Project Objectives

The main objectives of this project are to:

- Load and inspect the credit card transaction dataset.
- Understand the structure and characteristics of the data.
- Identify missing values and assess data completeness.
- Examine descriptive statistics for numerical variables.
- Detect and investigate potential outliers.
- Analyze the distribution of fraudulent and legitimate transactions.
- Explore relationships between important variables.
- Produce meaningful visualizations.
- Document important observations and insights from the analysis.

---

## Project Structure

The EDA folder contains the following files:


EDA/
│
├── README.md
│
├── [Dataset File]
│
└── [EDA Notebook].ipynb


# Retrieval-Augmented Generation (RAG) Pipeline

## Project Overview

This project implements a simple **Retrieval-Augmented Generation (RAG)** pipeline that allows a Large Language Model (LLM) to answer questions using information retrieved from a specific document.

The project demonstrates the complete RAG workflow:

1. Document ingestion
2. Text extraction
3. Text cleaning
4. Text chunking
5. Text embedding
6. Vector storage using FAISS
7. Similarity-based document retrieval
8. Context construction
9. LLM-based answer generation
10. Question-and-answer testing

The source document used in this project is:

**`History_and_Origin_of_Igbo_people_in_Nig.docx`**

The document is included in this project folder so that the RAG pipeline can be reproduced without needing to obtain the source document separately.

---

## Project Objectives

The main objectives of this project are to:

- Build a basic Retrieval-Augmented Generation system.
- Process a real-world `.docx` document.
- Divide the document into smaller text chunks.
- Convert text chunks into numerical embeddings.
- Store embeddings in a vector database.
- Retrieve the most relevant sections of the document for a user's question.
- Use an LLM to generate answers based on the retrieved information.
- Demonstrate the system using sample question-and-answer interactions.

---

## Project Structure

```text
RAG_Project/
│
├── History_and_Origin_of_Igbo_people_in_Nig.docx
│
├── RAG_Pipeline.ipynb
│
└── README.md








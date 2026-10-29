# AI Evaluation: ML, LLM, RAG & Agent Evaluation

## Overview

This repository contains my learning notes and practical implementations of **AI Evaluation**, covering traditional Machine Learning metrics, LLM evaluation techniques, Retrieval-Augmented Generation (RAG) evaluation, and AI Agent evaluation.

Understanding evaluation metrics is essential for building AI systems that are not only functional but also accurate, reliable, relevant, and trustworthy.

The concepts and implementations in this repository are demonstrated using Python and Google Colab.

## Topics Covered

### 1. Traditional Machine Learning Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- Macro, Micro, and Weighted F1
- ROC Curve and ROC-AUC
- Confusion Matrix
- Evaluation on Imbalanced Datasets

### 2. Text Generation Evaluation
- BLEU Score
- ROUGE-1, ROUGE-2, and ROUGE-L
- Semantic Similarity
- Text Embeddings
- Cosine Similarity

### 3. LLM-as-a-Judge
- Fundamentals of LLM-based evaluation
- Rubric-based scoring
- Correctness, relevance, and completeness
- Structured JSON evaluation
- Judge bias and limitations
- Improving evaluation reliability

### 4. RAG Evaluation
- RAG evaluation fundamentals
- Faithfulness
- Answer Relevance
- Context Precision
- Context Recall
- Answer Correctness
- Retrieval and Generation Failure Analysis

### 5. AI Agent Evaluation
- Task Success Rate
- Tool Selection Accuracy
- Tool Argument Evaluation
- Trajectory Evaluation
- Tool Call Efficiency
- Latency and Cost Analysis
- Agent Failure Analysis
- LangGraph Agent Evaluation Concepts

## Practical Implementations

The repository includes Python implementations demonstrating:

- Classification metrics using Scikit-learn
- BLEU and ROUGE for text-generation evaluation
- Semantic similarity using Sentence Transformers
- LLM-as-a-Judge using the Groq API
- Faithfulness and relevance evaluation examples
- Context precision and recall calculations
- AI Agent performance analysis using Pandas
- A combined evaluation experiment for comparing multiple metrics

All practical examples are designed to run in Google Colab.

## Technologies and Libraries

- Python
- Google Colab
- Scikit-learn
- NLTK
- ROUGE Score
- Sentence Transformers
- Pandas
- Matplotlib
- Groq API

## Key Learnings

Through these implementations, I explored:

- How to select appropriate evaluation metrics for different AI tasks.
- Why accuracy alone is insufficient for imbalanced datasets.
- The differences between lexical and semantic evaluation.
- How to assess grounding and relevance in RAG applications.
- How LLM-as-a-Judge can evaluate open-ended responses.
- How to evaluate AI Agents beyond their final answers.
- Why evaluation should include quality, reliability, latency, cost, and safety.

## Why AI Evaluation Matters

A model that generates an answer is not necessarily a model that generates a correct answer.

Systematic evaluation helps identify weaknesses, compare model versions, debug retrieval and generation failures, and improve the reliability of AI applications before deployment.

## Future Improvements

- Implementing RAG evaluation with Ragas or DeepEval.
- Evaluating real-world RAG datasets.
- Comparing LLM outputs against human judgments.
- Building automated evaluation pipelines.
- Integrating evaluation and regression testing into GenAI applications.

## Acknowledgements

This repository is part of my continuous learning journey in Machine Learning, Generative AI, RAG systems, and Agentic AI.

**Learning by building, evaluating, and improving AI systems.**

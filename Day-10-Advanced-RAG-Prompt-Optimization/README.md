# Day 10 - Advanced RAG and Prompt Optimization

## Project Title

**An Explainable LLM-Based Return Validation and Risk Assessment System Using RAG**

## Day 10 Objective

The objective of Day 10 is to improve the return validation system using advanced policy retrieval, optimized prompt engineering, decision consistency checks, and explainable decision tracing.

## Day 10 Activities

### 1. Advanced RAG Retrieval

An advanced retrieval query was created using:

- Product category
- Return reason
- Product condition
- Days after delivery
- Risk level
- Return validation requirements

Relevant policy documents were retrieved using semantic similarity with Sentence Transformers and FAISS.

### 2. Policy Relevance Analysis

Retrieved policies were analyzed using:

- FAISS distance
- Heuristic relevance score
- Retrieval rank

The retrieved policy evidence was used as the knowledge source for LLM validation.

### 3. Prompt Optimization

The LLM prompt was improved with strict validation rules.

The prompt instructs the system to:

- Use only provided information
- Avoid inventing policies
- Use retrieved policy evidence
- Consider risk level
- Consider validation guardrails
- Explain the final decision
- Provide a decision trace

### 4. Decision Consistency Guardrail

A consistency layer was added after LLM reasoning.

This prevents inconsistent outputs such as:

```text
Decision: REJECT
Recommended Action: REVIEW

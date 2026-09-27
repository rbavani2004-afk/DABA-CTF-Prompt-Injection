# Day 5 - Prompt Engineering and Validation Guardrails

## Project Title

**An Explainable LLM-Based Return Validation and Risk Assessment System Using RAG**

## Day 5 Objective

The objective of Day 5 is to improve the return validation system using prompt engineering and validation guardrails.

The system combines customer return information, risk analysis, retrieved policy evidence, and validation rules before generating the final LLM response.

## Day 5 Architecture

Customer Return Request  
↓  
Risk Score  
↓  
Risk Level  
↓  
RAG Policy Retrieval  
↓  
Validation Guardrails  
↓  
LLM Reasoning  
↓  
Decision + Explanation + Policy Evidence

## Prompt Engineering

A structured prompt was designed to guide the LLM to:

- Use only the provided information
- Use retrieved policy evidence
- Avoid inventing policy rules
- Consider the calculated risk level
- Follow validation guardrails
- Provide an explainable response

## Validation Guardrails

The system checks important return conditions such as:

- Return period exceeded
- Used product
- Damaged product
- High-risk return
- Outside policy period

Based on these conditions, the system can identify cases requiring additional validation or manual review.

## LLM Output

The validation response contains:

- Decision
- Risk Level
- Guardrail Status
- Reason
- Policy Evidence
- Policy Check
- Recommended Action
- Confidence

## Key Features

- Risk-based validation
- RAG-based policy retrieval
- Prompt engineering
- Validation guardrails
- Explainable LLM response
- Policy evidence
- Manual review detection

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Sentence Transformers
- FAISS
- Hugging Face LLM
- Matplotlib
- Seaborn

## Day 5 Outcome

At the end of Day 5:

- Prompt engineering was implemented.
- Dynamic policy retrieval was integrated.
- Validation guardrails were implemented.
- High-risk return cases were identified.
- Manual review conditions were detected.
- Explainable LLM validation responses were generated.
- Validation results were saved for further evaluation.

## Project Progress

**Day 5 - Completed**

**Next:** Day 6 - First Working Return Validation Assistant

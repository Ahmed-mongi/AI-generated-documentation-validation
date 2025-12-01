# AI-Assisted Code Summarization & Error Analysis  
**Phase 2 – Software Engineering with AI Project**

This repository contains a functional prototype, reproducible experiments, dataset, metrics, and report for Phase 2 of the project: **Integrating AI into a Software Engineering (SWE) task**.  
The implemented system uses Large Language Models (LLMs) to generate **code summaries** and analyze **defects or hallucinations** in model outputs.

---

## 📌 **Project Overview**
The goal of this project is to evaluate the performance and reliability of LLMs on a SWE-related task—specifically automated **code summarization** and **behavior explanation**.

This repository includes:

- A working prototype (Minimum Viable Product)
- Configurable model selection
- Prompt templates
- Automatic logging of prompts and responses
- Reproducible experiments + dataset preprocessing
- Early results, metrics, graphs
- Hallucination/error analysis table
- IEEE-style research report

---

# 🚀 **1. Prototype Implementation**

### **Features**
- Switch between AI models (GPT-4o mini, Llama-3, etc.)
- Customizable decoding parameters:
  - Temperature  
  - Top-k  
  - Max tokens  
- Prompt template system for:
  - Code summarization  
  - Defect explanation  
- Automatic logging:
  - Prompts  
  - Responses  
  - Model configs  
- Exportable metrics & evaluation results

### **Run the Prototype**
Install dependencies:

```bash
pip install -r requirements.txt

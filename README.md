# AI Code Documentation Validator & Generator

## Overview

This project implements an AI-powered system for generating and semantically validating code documentation. It addresses the challenge of ensuring accuracy and consistency in AI-generated docstrings by integrating a code generation component with a robust validation mechanism. The system uses PolyCoder-125M for code generation and CodeBERT for semantic validation via cosine similarity to detect "fabrication" hallucinations.

## Features

- **Code Generation**: Generate Python code snippets from natural language prompts using PolyCoder-125M.
- **Documentation Validation**: Validate the semantic consistency between code snippets and their docstrings using CodeBERT embeddings and cosine similarity.
- **Hallucination Detection**: Automatically flag potential fabrications where the documentation describes functionality not present in the code.
- **Web API**: RESTful API built with FastAPI for easy integration.
- **Interactive UI**: Streamlit-based frontend for demonstration and user interaction.
- **Batch Evaluation**: Automated evaluation scripts for assessing validator performance against ground-truth data.

## Architecture

The system consists of three main components:

1. **DocumentationValidator**: Uses CodeBERT to compute embeddings and cosine similarity for validation.
2. **CodeGenerator**: Leverages PolyCoder-125M to generate code from prompts.
3. **Data Handling**: Integrates with CodeSearchNet (CSN) dataset for evaluation.

## Installation

### Prerequisites

- Python 3.8+
- pip
- Git

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-code-doc-validator.git
   cd ai-code-doc-validator

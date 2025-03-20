# LLM-Based Automated Resume Matcher

## Overview
This project leverages the power of **Large Language Models (LLMs)** to automate the process of resume matching. It is designed to streamline recruitment workflows by accurately matching candidate resumes with job descriptions.

## Features
- **PDF Text Extraction**: Uses `PyPDF2` to extract text content from multi-page PDF files.
- **Generative AI Integration**: Implements the `gemini-pro` generative model for advanced content analysis and compatibility scoring.
- **Natural Language Processing**: Analyzes and aligns candidate qualifications with job requirements.
- **Scalable Architecture**: Optimized for large-scale recruitment processes with seamless integration into existing HR systems.

## How It Works
1. **Upload Resume**: The user uploads a candidate's resume in PDF format.
2. **Extract Text**: The `input_pdf_text()` function extracts text content using `PyPDF2`.
3. **Generate Matches**: The `get_gemini_response()` function processes the extracted text through the generative AI model to identify compatibility with job descriptions.
4. **Output Results**: The system provides a detailed compatibility score for easy evaluation.


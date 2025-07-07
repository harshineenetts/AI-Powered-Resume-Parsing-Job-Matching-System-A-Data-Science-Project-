# AI-Powered Resume Parsing & Job Matching System

This project automates the process of extracting structured data from unstructured PDF resumes and evaluates how well a candidate matches a given job description using modern NLP techniques.

## 🔍 Features

- **Resume Parsing with LLMs**: Extract structured data such as name, education, experience, skills, etc., using Groq’s LLaMA 3 via LangChain.
- **Validated Output**: Structured output enforced using Pydantic models.
- **Job Role Matching**: Calculates semantic similarity between resumes and job descriptions using sentence embeddings and cosine similarity.
- **PDF Support**: Load and parse resumes in `.pdf` format using PyPDFLoader.
- **Scoring System**: Returns match scores and interprets them (Excellent, Good, Weak).

## 🛠️ Tech Stack

- Python
- LangChain
- Groq (LLaMA 3-70B)
- Pydantic
- Sentence Transformers (`all-MiniLM-L6-v2`)
- PyPDFLoader
- Scikit-learn

## 🚀 Use Case

Ideal for automating candidate screening and shortlisting in recruitment pipelines.

## 📂 Project Structure


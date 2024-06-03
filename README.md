# Langchain-con-Ollama

Langchain repo with Ollama and Llama 3 - 8b integration for RAG

## Se debe crear un ambiente virtual con poetry

[tool.poetry]
name = "local-chatbot"
version = "0.1.0"
description = "Un chatbot con base de datos local sobre chroma, LLM local con llama 3 y Ollama y Langchain como framework"
authors = ["Sandra Rairan <sandrarairan@gmail.com>"]
readme = "README.md"

[tool.poetry.dependencies]
python = ">=3.9,<3.13"
langchain = "^0.1.17"
langchain-community = "^0.0.37"
PyMuPDF = "^1.24.2"
chromadb = "^0.5.0"
fastembed = "^0.2.7"


[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"


sandrarairan/Langchain-con-Ollama replicando lo aprendido del canal Carlos Alarcón - AI

# Givana Social Media RAG System

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system for automated social media content planning for an e-commerce gift shop.

The system:
- Crawls live product pages
- Builds semantic embeddings
- Stores them in a FAISS vector database
- Uses an LLM (Flan-T5) for caption generation
- Applies similarity control to avoid repetitive posts
- Generates a 30-day social media calendar

## Architecture

Crawler → Chunking → Embeddings → FAISS → Retrieval → LLM → Similarity Guard → Calendar CSV

## Key Features

- Live product crawling from WooCommerce shop page
- Semantic retrieval using sentence-transformers (all-MiniLM-L6-v2)
- Vector similarity search via FAISS
- Local LLM (google/flan-t5) integration
- Caption-only similarity control
- Automated posting time suggestion
- Exportable 30-day content plan

## Technologies Used

- Python
- Pandas
- Sentence Transformers
- FAISS
- HuggingFace Transformers
- BeautifulSoup
- Google Colab

## Output

The system generates:
- `givana_30_day_calendar_LLM_RAG.csv`

Columns include:
- Day
- Product
- Post Type
- Theme
- Suggested Time
- Caption
- Hashtags
- Similarity Score

## Future Improvements

- Multi-platform tone adaptation
- n8n automation integration
- Scheduled execution pipeline
- Deployment-ready API wrapper

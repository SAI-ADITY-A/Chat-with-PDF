# Chat with Multiple PDFs

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://chat-p-df.streamlit.app/)

This project is a PDF-based question-answering app that allows users to interact with multiple PDF files by asking questions and receiving relevant answers. Built with Streamlit, FAISS, PyPDF2, and Google Generative AI, the app leverages embeddings to index PDF content and retrieve answers based on user queries.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Multi-PDF Upload**: Upload multiple PDF files and analyze them together.
- **Question-Answering**: Ask questions, and the app fetches answers based on the indexed PDF content.
- **Embeddings with FAISS**: Uses FAISS for efficient text chunk indexing and similarity search.
- **Google Generative AI**: Employs Google Generative AI for question-answering with custom prompts.
- **Streamlit Interface**: Provides an interactive web interface with options to upload files and ask questions.

## Tech Stack
- **Streamlit**: For the web interface.
- **FAISS**: For vector indexing and similarity search.
- **PyPDF2**: To extract text from PDFs.
- **Google Generative AI**: For embeddings and generating responses.

## [Live Demo](https://chat-p-df.streamlit.app/)

## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Chat-with-multiple-PDFs.git
   cd Chat-with-multiple-PDFs
   ```
2. **Install Dependencies**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Environment Variables**

Create a .env file in the root directory.

Add your Google API Key:
  ```bash
  GOOGLE_API_KEY=your_google_api_key_here
  ```


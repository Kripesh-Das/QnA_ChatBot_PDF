# Conversational RAG with PDF Uploads and Chat History

This project is a Streamlit application that allows users to upload PDF files and interact with their content through a conversational interface. The application uses a Retrieval-Augmented Generation (RAG) approach to answer user questions based on the uploaded documents and maintains a chat history for context-aware interactions.

## Features

- **PDF Upload**: Upload multiple PDF files to the application.
- **Conversational Interface**: Ask questions about the content of the uploaded PDFs.
- **Chat History**: Maintain a chat history to provide context-aware responses.
- **Retrieval-Augmented Generation**: Use a combination of document retrieval and language generation to answer questions.

## Requirements

- Python 3.11
- Streamlit
- LangChain
- LangChain Chroma
- LangChain Core
- LangChain Community
- LangChain Groq
- LangChain HuggingFace
- ChromaDB
- PyPDFLoader
- dotenv

## Installation

1. Create a virtual environment and activate it. [Note that venv python 3.11 was used for this project]
2. Install the required packages.
3. Create a `.env` file and add your HuggingFace token:
    ```env
    HF_TOKEN=your_huggingface_token
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your browser and go to `http://localhost:8501`.

3. Enter your Groq API key when prompted.

4. Upload PDF files and start asking questions!

## Additional Information
- Folder project_demonstration has screenshots of the working model on streamlit.

## Project Structure

- `app.py`: Main application file.
- `requirements.txt`: List of dependencies.
- `.env`: Environment variables file (not included in the repository).

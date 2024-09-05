# Document Querying with Retrieval-Augmented Generation using LLMs

## Overview

This project, **Document Querying with Retrieval-Augmented Generation using LLMs**, is designed to provide efficient document querying by combining retrieval mechanisms with large language models (LLMs). The system includes a backend built with FastAPI and the LangChain framework, along with a React.js frontend that allows users to upload documents and submit queries.

## Project Description

- **Backend**: Built using FastAPI and LangChain, the system enables efficient querying by retrieving relevant document sections and using LLMs to generate answers based on the retrieved context.
  
- **Frontend**: The React.js interface allows users to upload documents and interact with the querying system, making the process user-friendly and accessible.

### Key Features:
- **Document Upload**: Users can upload PDF documents to the system.
- **Retrieval-Augmented Generation**: Combines document retrieval techniques with LLMs to generate accurate and contextually relevant responses.
- **Interactive UI**: React.js interface facilitates easy query submission and result review.

## Tech Stack

- **Backend**:
  - FastAPI
  - LangChain
- **Frontend**:
  - React.js
- **Language Models**: Integrated via LangChain to enhance document querying.

## Installation

### Prerequisites

- Python 3.8 or later
- Node.js
- Install dependencies from the `requirements.txt` and `package.json` files.

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/mohd-adil-khan/DocumentRAG.git
    cd DocumentRAG
    ```

2. **Backend Setup**

    1. Navigate to the backend directory:
    
    ```bash
    cd backend
    ```

    2. Set up a virtual environment and install the required dependencies:

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    pip install -r requirements.txt
    ```

    3. Run the FastAPI backend:

    ```bash
    uvicorn app:main --reload
    ```

3. **Frontend Setup**

    1. Navigate to the frontend directory:

    ```bash
    cd frontend
    ```

    2. Install the necessary packages:

    ```bash
    npm install
    ```

    3. Start the React.js development server:

    ```bash
    npm start
    ```

## Usage

1. **Upload Documents**: Use the frontend interface to upload documents in PDF format.
2. **Submit Queries**: Enter your query in the search bar, and the system will retrieve relevant sections of the document and generate a response.
3. **Review Responses**: The system will return an LLM-generated response based on the document context.

## File Structure

- **backend/**: Contains the FastAPI server and LangChain integration.
- **frontend/**: React.js application for document upload and query processing.
- **requirements.txt**: Python dependencies for the backend.
- **package.json**: Node.js dependencies for the frontend.
- **README.md**: Project documentation.

## Results

The project enables efficient and context-aware document querying, delivering relevant responses using retrieval-augmented generation. The system can handle a wide range of document types and queries, providing a robust solution for document-based question answering.

## Contributions

Contributions are welcome! Please feel free to open issues or submit pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- **FastAPI**: For the robust backend framework.
- **LangChain**: For enabling efficient document querying with LLMs.
- **React.js**: For the interactive and user-friendly frontend interface.

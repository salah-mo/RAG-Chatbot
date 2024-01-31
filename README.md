# RAG Chatbot (Retrieval-Augmented Generation)

This project allows users to upload multiple PDF documents and ask questions about the content of these documents. The
application uses language models and vector stores to retrieve relevant information from the documents and provide
responses to the user's queries.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing
purposes.

### Prerequisites

- Python
- pip

### Installing

Clone the repository to your local machine:

```bash
git clone <repository_url>
```

Navigate to the project directory:

```bash
cd <project_directory>
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## Running the Application

To run the application, execute the following command:

```bash
python RAGWithHF.py
```

## Usage

1. Open the application in your web browser.
2. Upload your PDF documents using the file uploader in the sidebar.
3. Click on 'Process' to process the uploaded documents.
4. Ask a question about your documents in the text input field.
5. The application will display the response to your question.

## Built With

- [Streamlit](https://streamlit.io/) - The web framework used
- [PyPDF2](https://pythonhosted.org/PyPDF2/) - A library used to read PDF documents
- [langchain](https://github.com/langchain/langchain) - A library used for text splitting, embeddings, vector stores,
  and conversation models
- [dotenv](https://github.com/theskumar/python-dotenv) - A library used to manage environment variables

## Authors

- Salah Mo - Initial work

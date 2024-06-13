# Document Q&A

This project implements a Document Q&A application using LangChain, Streamlit, and various other components for document processing, embedding, and querying. The application allows users to upload PDF documents, create vector embeddings from these documents, and query the documents for specific information.

## Requirements

1. Python 3.7+
2. Required Python packages (listed in `requirements.txt`)
3. GROQ API Key and Google API Key for embeddings

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows: `env\Scripts\activate`

3. Install the required packages:
    ```bash
    pip install -r requirements.txt

4. Create a .env file in the root directory and add your API keys:
    ```bash
    GROQ_API_KEY=your_groq_api_key
    GOOGLE_API_KEY=your_google_api_key

5. Start the Streamlit application:
    ```bash
    streamlit run app.py
    
App link: https://document-q-a-ia2w8xv2mvkgqbuxlr5mpj.streamlit.app/






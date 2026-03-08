# RAG Chatbot

This project is a Retrieval-Augmented Generation (RAG) chatbot built using Streamlit and LangChain. It allows users to upload PDF files and interact with the content through a chatbot interface.

## Features
- Upload multiple PDF files.
- Extract and process text from PDFs.
- Use LangChain for text splitting and embedding.
- FAISS for vector storage and similarity search.
- Streamlit for a user-friendly web interface.

## Requirements
Install the required Python packages using the following command:

```bash
pip install -r requirements.txt
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Hirthick7/Rag.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Rag
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Project Structure
- `app.py`: Main application file.
- `requirements.txt`: List of dependencies.

## License
This project is licensed under the MIT License.
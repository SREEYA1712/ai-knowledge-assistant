# ai-knowledge-assistant

# AI Knowledge Assistant

## Project Overview
AI Knowledge Assistant is a document-based question-answering application that helps users retrieve information from uploaded documents using Artificial Intelligence.

Users can upload documents, ask questions in natural language, and receive answers based on the information available in the documents.

The goal is to make document searching faster, easier, and more interactive.

## Key Features

- Upload and process documents.
- Ask questions using natural language.
- Retrieve relevant information from documents.
- Generate AI-powered answers based on document content.
- Provide source references to help users verify answers.
- Simple and interactive user interface using Streamlit.

## Technologies Used

- **Python** – Core programming language.
- **Streamlit** – Web application interface.
- **LLM (Large Language Model)** – Answer generation.
- **Vector Database (ChromaDB)** – Document embedding storage and retrieval.
- **Embeddings** – Convert text into numerical representations for similarity search.
- **Natural Language Processing (NLP)** – Process and understand text.

*Note: Keep only the technologies actually used in your implementation.*

## Project Structure

```text
ai-knowledge-assistant/
│
├── app.py
├── requirements.txt
├── README.md
└── other project source files
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/SREEYA1712/ai-knowledge-assistant.git
```

### 2. Navigate to the project folder

```bash
cd ai-knowledge-assistant
```

### 3. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser.

## How It Works

1. User uploads a document.
2. The application extracts and processes the document text.
3. Text is converted into embeddings.
4. Relevant information is retrieved based on the user's question.
5. The AI generates an answer using the retrieved information.
6. Relevant sources are presented for verification.

## Future Improvements

- Support for additional document formats.
- Improved answer accuracy.
- Better source citation and retrieval.
- Enhanced user interface.
- Support for multiple documents.

## Author

**Sreeya Tirumalasetti**

Master's Student – Applied Artificial Intelligence  
University of Wollongong in Dubai

---

⭐ If you find this project useful, feel free to explore the repository!

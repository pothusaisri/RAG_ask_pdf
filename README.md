# 📚 Ask Your PDF - AI-Powered Document Analysis Tool

To try clone repo and do the following

Transform static PDFs into interactive knowledge bases using cutting-edge AI. This application combines NLP capabilities with document intelligence for context-aware Q&A.

## ✨ Features
- **Deep Document Analysis** - Complex structure parsing
- **Precision Responses** - Context-grounded answers
- **Local AI Processing** - Ollama-powered inference
- **Secure Environment** - In-memory data handling
- **Developer-First UI** - Dark theme with custom styling

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- [Ollama](https://ollama.ai/) installed
- DeepSeek-R1 model:  
  ```bash
  ollama pull deepseek-r1
  ```
- Install Dependencies:
  ```bash 
  pip install -r requirements.txt
  ```
### 🖥 Usage
    ```bash
    streamlit run app.py
    ```
Workflow:

Upload PDF via file dialog
Wait for processing confirmation (✅)
Ask questions in chat interface

Sample Queries:

"Explain the methodology section"
"List key findings from page 12"
"Compare results in tables 3 and 4"

📊 System Architecture

[PDF Upload] → [Text Extraction] → [Chunking]  
             → [Embeddings] → [Vector Store]  
             → [Query] → [Context Retrieval]  
             → [LLM Synthesis] → [Response]

📌 Notes
Initial launch requires model loading time
Recommended 8GB+ RAM for optimal performance
Supported browsers: Chrome, Firefox, Edge
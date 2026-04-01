 AI PDF Chatbot using RAG and LLM

 Description
This project is an AI-powered chatbot that answers questions from PDF documents using Retrieval-Augmented Generation (RAG). It combines document retrieval with language models to provide accurate, context-aware answers.

 Features
- Upload PDF and extract text
- Chunk text into smaller segments
- Convert text into embeddings
- Store embeddings in FAISS vector database
- Retrieve relevant content based on user query
- Generate answers using LLM (GPT-2)

 How It Works

1. PDF is uploaded by the user  
2. Text is extracted from the document  
3. Text is split into chunks  
4. Each chunk is converted into embeddings  
5. Embeddings are stored in FAISS  
6. User enters a query  
7. System retrieves relevant chunks  
8. LLM generates final answer  

 Tech Stack
- Python  
- LangChain  
- FAISS  
- HuggingFace Transformers  
- Google Colab  
 Architecture

User Query → Embedding → FAISS Search → Context Retrieval → LLM → Final Answer

 Example

**Input:**  
What is this document about?

**Output:**  
The document discusses key concepts related to the topic and provides detailed explanations based on the content.

 Output Screenshot
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/11a73f94-4d31-4285-b994-717aafe56cf2" />


 Applications
- Document Q&A systems  
- Research assistance  
- Knowledge retrieval  
- AI assistants  

 Future Improvements
- Add web interface (Streamlit)  
- Use advanced LLMs (GPT-3/4)  
- Support multiple PDFs  
- Improve response accuracy  

 Conclusion
This project demonstrates how Retrieval-Augmented Generation (RAG) can be used to build intelligent systems that understand and respond based on document content, making it useful for real-world AI applications.

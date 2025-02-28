### Programming Language:
- **Python**: The entire implementation is written in Python.

### Libraries and Frameworks:

#### **LangChain**:
- Used for integrating language models, embeddings, and vector stores.
  
  **Key Components:**
  - **ChatGroq**: For interacting with the Groq Llama model.
  - **HuggingFaceEmbeddings**: For generating embeddings using Hugging Face sentence-transformers.
  - **FAISS**: For creating and querying a vector store for efficient similarity search.
  - **CharacterTextSplitter**: For splitting text into chunks for embedding and storage.

#### **Hugging Face**:
- Used for embeddings via the `sentence-transformers/all-MiniLM-L6-v2` model.

#### **Groq**:
- Used for the Llama-3.3-70b model to generate interview questions.

#### **JSON**:
- Used for loading and parsing the projects dataset.

#### **FAISS (Facebook AI Similarity Search)**:
- Used for creating a vector store to index and retrieve relevant questions efficiently.

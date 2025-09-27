# RAG Workshop 2 - Enhanced Learning Materials

This repository contains comprehensive educational materials for learning **GraphRAG** and **Multimodal RAG** implementations, with detailed explanations and step-by-step tutorials.

## 🚀 What's Inside

### 📚 Enhanced Notebooks with Comprehensive Explanations

#### 1. **GraphRAG Implementation** (`graph_rag.ipynb`)
- **Complete GraphRAG Pipeline**: From data ingestion to intelligent candidate recommendations
- **3-Stage Process Explained**:
  - Stage 1: Semantic Search using vector embeddings
  - Stage 2: Graph Traversal for filtering and augmentation
  - Stage 3: LLM-powered response generation
- **Neo4j Integration**: Full knowledge graph setup and management
- **Real-world Use Case**: Recruitment co-pilot system

#### 2. **Multimodal RAG Implementation** (`multimodal_rag.ipynb`)
- **Two Approaches Demonstrated**:
  - Approach 1: Raw image retrieval from image files
  - Approach 2: Mixed content retrieval from parsed documents
- **OpenCLIP Integration**: Multimodal embeddings for images and text
- **ChromaDB Vector Store**: Efficient similarity search
- **Image Processing**: Base64 encoding, resizing, and display utilities

### 🔧 Technical Features

- **Detailed Code Comments**: Every line explained for educational purposes
- **Step-by-step Breakdowns**: Complex concepts made accessible
- **Best Practices**: Production-ready patterns and optimizations
- **Error Handling**: Robust implementations with proper exception handling
- **Cost Optimization**: Image resizing and efficient embedding strategies

## 🛠️ Tech Stack

- **Neo4j**: Graph database for knowledge graphs
- **OpenAI**: GPT-4 for LLM and text embeddings
- **LangChain**: RAG pipeline orchestration
- **ChromaDB**: Vector database for embeddings
- **OpenCLIP**: Multimodal embeddings
- **PyMuPDF**: PDF processing
- **Python**: Core programming language

## 📋 Prerequisites

- Python 3.8+
- OpenAI API key
- Neo4j database access
- Git

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/Jasonpereira0/RAG-Workshop-2.git
cd RAG-Workshop-2
```

### 2. Set Up Virtual Environment
```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Environment Setup
**🔒 SECURITY IMPORTANT:** Never commit real credentials to version control!

1. **Copy the environment template:**
```bash
cp .env.example .env
```

2. **Edit the `.env` file with your actual credentials:**
```env
OPENAI_API_KEY=your_actual_openai_api_key_here
NEO4J_URI=your_actual_neo4j_uri_here
NEO4J_USERNAME=your_actual_neo4j_username_here
NEO4J_PASSWORD=your_actual_neo4j_password_here
```

3. **Verify your `.env` file is in `.gitignore`** (it should be automatically ignored)

**Security Best Practices:**
- ✅ Use environment variables for all credentials
- ✅ Never hardcode passwords in source code
- ✅ Rotate credentials regularly
- ✅ Use different credentials for development/production
- ✅ Consider using secret management services in production

### 5. Run the Notebooks
Start Jupyter Lab or Jupyter Notebook:
```bash
jupyter lab
# or
jupyter notebook
```

## 📖 Learning Path

### For Beginners:
1. Start with `graph_rag.ipynb` - Cell by cell execution
2. Understand the 3-stage GraphRAG process
3. Experiment with different queries and filters
4. Move to `multimodal_rag.ipynb` for advanced concepts

### For Advanced Users:
1. Explore the complete pipeline implementations
2. Study the optimization techniques
3. Modify the prompts and retrieval strategies
4. Implement your own use cases

## 🎯 Key Learning Outcomes

After completing this workshop, you'll understand:

- **GraphRAG Architecture**: How knowledge graphs enhance traditional RAG
- **Vector Search**: Embedding-based similarity search
- **Graph Traversal**: Filtering and augmentation techniques
- **Multimodal AI**: Processing images and text together
- **Production Patterns**: Scalable RAG implementations
- **Cost Optimization**: Efficient embedding strategies

## 🔍 What Makes This Special

- **Educational Focus**: Every concept explained in detail
- **Real-world Applications**: Practical use cases you can build upon
- **Production Ready**: Code patterns used in industry
- **Comprehensive Coverage**: From basics to advanced techniques

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements:
- Additional explanations
- Bug fixes
- New examples
- Documentation improvements

## 📄 License & Credits

**Educational Content**: This repository contains educational materials and code examples.

**Workshop Content**: Original workshop materials and concepts are credited to **The Gen Academy**. This repository serves as an enhanced learning resource with comprehensive explanations added for educational purposes.

## 🌟 Star the Repository

If you found this helpful, please give it a star! ⭐

## 📞 Contact

For questions or suggestions, please open an issue in this repository.

---

**Happy Learning! 🚀**
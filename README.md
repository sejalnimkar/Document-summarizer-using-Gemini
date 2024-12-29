## Chat with PDFs using Gemini 💁
**This project is a Streamlit-based web application that allows users to upload PDF files and interact with their content using advanced AI capabilities. The app extracts text from PDF documents, processes it into manageable chunks, and creates a vector-based index using FAISS and Google Generative AI embeddings. Users can then ask questions about the content of the uploaded PDFs, and the app responds with detailed, context-aware answers.**

**Key Features:**
- PDF Parsing: Extracts text from uploaded PDF files using PyPDF2.
- Text Chunking: Splits the extracted text into manageable chunks for efficient processing.
- Vector Store Creation: Stores text chunks as embeddings in a FAISS vector store for similarity-based retrieval.
- AI-Powered QA: Uses Google Generative AI (via LangChain) to generate accurate answers to user questions based on the PDF content.
- Interactive UI: A user-friendly interface built with Streamlit for easy interaction.

**How It Works:**
- Upload one or more PDF files.
- The app extracts text, processes it into chunks, and creates a FAISS index.
- Enter a question in the text input field, and the app retrieves relevant content and generates a detailed answer.

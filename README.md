# Introduction to Retrieval Augmented Generation

This repository will introduce you to Retrieval Augmented Generation (RAG) with
easy to use examples that you can build upon. The examples use Python with
Jupyter Notebooks and CSV files. The vector database uses the Qdrant database
which can run in-memory.

**Install the dependencies**

Create the virtual environment and install the dependencies:

```
python3 -m venv .venv
.venv\Scripts\activate
.venv\Scripts\pip.exe install -r requirements.txt
```
### Summary of changes:

- Added `tweets.csv` Data.   
- Clarified that only **Qdrant** and **Sentence Transformers** are used here for vector DB + embeddings.  
- Added note about using **LangChain Groq** with Groq API key instead of Llamafile or OpenAI API.  

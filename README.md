# FAISS-RAG-GPT2-Experiments  

🔍 Testing Retrieval-Augmented Generation (RAG) using FAISS (CPU), GPT-2, and parameter tuning.  

## Features  
- FAISS (CPU) for efficient similarity search.  
- GPT-2 for text generation.  
- Parameter tuning (e.g., top-k retrieval, temperature).  
- Basic RAG pipeline for QA or text augmentation.  

## Setup  
1. Clone the repo
2. nstall dependencies


   Usage
Run the RAG pipeline:

python
Copy
python rag_pipeline.py --query "Your question here" --top_k 5  
Parameters
--query: Input query for retrieval.

--top_k: Number of FAISS-retrieved passages.
   

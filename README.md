## Document Analysis with LLM
Split documents into passages and generate questions and answers.
- Extracts text from PDF.
- Summarizes entire document using an Open source LLM.
- Splits document into sentences using the nltk library.
- Generates for each sentence using LLM.
- Answers question from passage.


## Document RAG analysis with open source LLM
Uses RAG to answer questions from document.
- Loads text documents and split into chunks using langchain text splitters library.
- Create embeddings from chunks using transformers and all-MiniLM-L6-v2 model.
- Creates a vector store to store embeddings with fiass library.
- Answers questions from document by searching for closest embeddings and passing it to an open source question answering LLM.


## AI Resume Screener with Ollama & LLama3
- Analyzes a resume against a job description 
- Returns a summary if resume is fit for the role or not.

## A web search tool with Ollama
- Calls a tool using Ollama and llama3.1 to search the web for result
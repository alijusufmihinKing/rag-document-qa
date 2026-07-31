# rag-document-qa
A document assistant that answers user questions based on the document

# How RAG works
1.Break the document into small chunks

2.When a question comes up, find the right chunk

3.Send the question + the right chunk to Claude

# Tech Stack
Python,

Anthropic

Architecture: RAG (Retrieval-Augmented Generation)

Embeddings: all-MiniLM-L6-v2 (via ChromaDB)

# Example:
Question: What happened in the Spain vs Cape Verde match?

Answer: 

According to the text, the match ended in a **0:0 draw**.

This unexpected result is highlighted as an example of an upset that negatively affected bettors who had included Spain's victory in accumulator (parlay) bets, since the draw "wrecks the whole chain" of combined bets.

# Important!!!
To run this yourself, add your Anthropic API key via Kaggle Secrets (Add-ons → Secrets) with the label ANTHROPIC_API_KEY.

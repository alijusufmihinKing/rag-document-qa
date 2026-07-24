# rag-document-qa
A document assistant that answers user questions based on the document

# How RAG works
1.Break the document into small chunks

2.When a question comes up, find the right chunk

3.Send the question + the right chunk to Claude

# Tech Stack
Python, Anthropic
Architecture: RAG (Retrieval-Augmented Generation)

# Example:
Question: What happened in the Spain vs Cape Verde match?

Answer: 

Spain - Cape Verde Match Result
According to the text, the match between Spain and Cape Verde ended in a **0:0 draw**.
This result was significant because:

1. It was unexpected** - The odds heavily favored Spain (1.08), implying a 92.5% probability of a Spain win
2. It was profitable for bookmakers** - The draw generated substantial profit for bookmakers. In the example given, if 70,000 rubles were bet on a draw at 11.9 odds, the bookmaker would profit 167,000 rubles from that outcome alone
3. **It hurt accumulator bettors** - The unexpected draw "wrecked" parlays (accumulator bets) where bettors had combined Spain's expected win with other similarly favored outcomes
4. **It was the most profitable match** - This Spain-Cape Verde match brought Russian bookmakers the largest combined profit of the tournament, according to data cited in the text

The match exemplifies how upsets and unexpected results generate significant profits for bookmakers, especially when they involve heavily favored teams drawing or losing against underdogs.

# Important!!!
To make the assistant work, you must insert your API key instead of "API-KEY".

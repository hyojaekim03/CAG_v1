# CAG_v1
Cache Augmented Generation Implementation

### Paper
---
https://arxiv.org/html/2412.15605v1

### What is CAG?
---
CAG is an alternate paradigm to RAG. RAG is known to embed entire knowledge bases using an embedding model into a vector database. Then a user query is embedded using the same embedding model, compared against embeddings in the vector database, and fetches the most relavant documents based on a similarity search. 
CAG offers a simpler approach. If your external knowledge base is of a manageable size, CAG involves directly including the entire knowledge base within the prompt along with the query. The LLM can then process both the query and the knowledge base to generate a response. This strategy eliminates the need for a vector database and similarity calculations. CAG benefits from the recent advancements in LLMs, such as models like Llama, Mixtral, and Gemma, which demonstrate improved performance and efficiency with larger context windows.

Source: https://medium.com/@sabaybiometzger/cache-augmented-generation-cag-from-scratch-441adf71c6a3

### Diagram
---
<img width="758" alt="Screenshot 2025-03-22 at 12 48 23 AM" src="https://github.com/user-attachments/assets/73faf080-7f2d-48d2-8120-1de27ed755b3" />

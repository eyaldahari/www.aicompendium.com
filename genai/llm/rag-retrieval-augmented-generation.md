# RAG (Retrieval Augmented Generation)

When to use RAG

LLM do not remember facts. In contrast to Database, it remembers probabilities (when used for information retrieval). LLM do not remember quotes like "Sam Altman is the CEO of Open AI". It can output that with high probability when asked who is OpenAI CEO at 2024? If facts needs to be retrieved, and especially when those facts are not part of the LLM trained, data can use RAG to Augment that into LLM. RAG we can provide our local domain data and LLM will use it. In addition, LLM has a short context window and we cant provide it all our company documents for instance

| RAG Pros |                                                                                        |
| -------- | -------------------------------------------------------------------------------------- |
|          | Cheaper than fine tune                                                                 |
|          | Easy to keep up to date                                                                |
|          | Reduce hallucinations and errors                                                       |
|          | Ability to show the REAL actual documents from which answer is taken from              |
| RAG Cons |                                                                                        |
|          | a lot of muving  parts                                                                 |
|          | deep dependency on vector DB and risk of non matching embeddings, maintaining versions |
|          | Hard to constomize                                                                     |

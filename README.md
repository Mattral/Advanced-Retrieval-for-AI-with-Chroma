# Advanced-Retrieval-for-AI-with-Chroma

A common workflow in RAG is to take your query and embed that, 
then find the most similar documents, meaning ones with similar embeddings, 
and that's the context. But the problem with that 
is that it can tend to find documents that talk about similar 
topics as a query, but not actually contain the answer. But 
you can take the initial user query and rewrite. 
This is called query expansion. 
Rewrite it to pull in more directly related documents. 
Two key related techniques. One, to expand the optional 
query into multiple queries by rewording or rewriting 
it in different ways. And second, to even guess or hypothesize what 
the answer might look like to see if we can find anything 
in our document collection that looks more like an 
answer rather than only generally talking 
about the topics of the query. 

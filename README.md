# embed_search
This project helps to understand how does the embedding search is processed.
In this project Hierarchical Navigable Small World technique with used. 
This technique is an Approximate Nearest Neigbour algorithm which allows to approximately 
find the best suited embeddings from the embedding database  with much less compute in compare to KNN.
This solution isvolves nither Langchain nor Llama_index but shows how deals are done in those two frameworks.
The database is the text which was just cut by pieses of 500 chars with no any preprocessing so that is why the result of serch was not always good.
This project is done only for educational purposes to give understand of how it works.
The most of actiions is done in notebook.ipynb and the most of magic (I mean HNSW) in utils.py.
Thanks for visiting)

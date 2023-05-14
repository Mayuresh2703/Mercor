# Mercor
To implement a semantic search using artificial intelligence.We will develop a search engine that encodes the user's query into a vector and searches for similarity within a body of text. The user can store all the text to be searched using a vector database like Pinecone. This search engine will be designed to provide accurate and relevant search results.

#Required Components

1. Vector Database: You will need to choose a vector database like Pinecone to store the text that will be searched. The vector database will be used to store and index the text documents.

2. Vectorization Algorithm: You will need to implement a vectorization algorithm that encodes the text documents into a vector representation. You can use Open AI’s latest text embeddings to vectorize the search query and the text documents to be searched from.

3. Similarity Search Algorithm: You will need to implement a similarity search algorithm that can find the most similar documents to the user's query. The algorithm should be optimized for speed and accuracy.

4. User Interface: You will need to develop a user interface that allows users to enter their queries and view the search results. The interface should be intuitive and easy to use. You're welcome to use a UI template if that is easier.

As we are building a AI semantic search engine we need a database designed specifically for handling this type of data. Vector databases like Pinecone fulfill this requirement by offering optimized storage and querying capabilities for embeddings.It consists of index,collection and Api-keys.

An index is the highest-level organizational unit of vector data in Pinecone. It accepts and stores vectors, serves queries over the vectors it contains, and does other vector operations over its contents. Each index runs on at least one pod.

Collections are used for takking a snapshot of the data in you index.To create a collection
first an index then click 'Create Collection'.

API stands for Application Programming Interface. In the context of APIs, the word Application refers to any software with a distinct function. Interface can be thought of as a contract of service between two applications. This contract defines how the two communicate with each other using requests and responses.

Python Libraries used->
Open ai
nltk
AutoTokenizer and AutoModel from transformers
torch
numpy
GPT2Tokenizer, GPT2LMHeadModel from transformers
IPyWidgets

In our code IPyWidgets is used as UI as it is HTML interactive widgets for Jupyter notebook.Each UI element in the library can respond to events and invokes specified event handler functions. They enhance the interactive feature of Jupyter notebook application.



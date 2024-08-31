# vector_store_FAISS
In this demo, we will learn on how to review user comments and get meaningful insights from the reviews.

AMAZON user reviews: The data set used is amazon_user_reviews which can be downloaded from internet
Below are the detailed steps to achieve this:
1. Convert the reviews text column to embeddings using sentence transformer
2. Save the embeddings to the disk to load it whenever required
3. Install FAISS vector store and upload the embeddings into FAISS vector store
4. FAISS vector store will help to retrieve similiar documents very efficiently
5. Create a function to retrieve top 1000 similiar documents based on user input
6. Pass these documents to claude LLM and write prompt to enable LLM review the comments and
   provide meaningful insights
7. User input needs to be the product name so that we can get detailed summary of positive and negative comments and areas of improvement for the product


# Gen-AI-Project--Create-and-Configure-a-Vector-Database-to-Store-Document-Embeddings
# Building a Vector Database for Semantic Search

[![LangChain](https://img.shields.io/badge/LangChain-0086CB?style/for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNTYgMjU2Ij48cGF0aCBkPSJNMjI0IDQ4YTY0IDY0IDAgMCAwLTkwLjQ5IDBMMTE3LjI3IDY0SDEwNGE0MCA0MCAwIDEgMC00MCA0MGwtMTguNzUgMTguNzVBMTYgMTYgMCAwIDAgNDAgMTM2djY0YTMyIDMyIDAgMCAwIDMyIDMySDI0MGEzMiAzMiAwIDAgMCAzMi0zMmwzMi0zMmE2My44MSA2My44MSAwIDAgMC04MC04MCIgc3R5bGU9ImZpbGw6IzAwODZjYiIvPjwvc3ZnPg==)](https://www.langchain.com/)
[![watsonx.ai](https://img.shields.io/badge/IBM%20watsonx.ai-0062FF?style/for-the-badge&logo=ibm&logoColor=white)](https://www.ibm.com/watsonx)

A hands-on lab on creating and configuring a **vector database** to store and query document embeddings for a fast and accurate semantic search system.

---

## 📖 The Challenge

Imagine a busy customer support center. When a new ticket arrives, agents waste valuable time manually searching through FAQs and past inquiries with slow, keyword-based tools. This leads to delayed responses and unhappy customers.

The solution is to build an intelligent, **semantic search** system. We will convert all support documents and past tickets into numerical vectors (**embeddings**) that capture their meaning. These embeddings will then be stored in a specialized **vector database**, allowing agents to find the most relevant information instantly.

In this lab, you'll learn how to build this system using embeddings from **watsonx.ai** and storing them in two popular vector databases: **Chroma DB** and **FAISS**. ⚡



---

## 🔬 Core Concepts

* **Document Embedding:** The process of converting text into meaningful numerical vectors using a model like the one from **watsonx.ai**.
* **Vector Database:** A database specifically designed to store and efficiently query high-dimensional vectors. Instead of looking for exact matches, it finds the "nearest neighbors" to a query vector, enabling search based on semantic similarity.
* **Similarity Search:** The process of taking a new query (e.g., a customer's question), converting it into a vector, and using the vector database to find and retrieve the most similar (and thus most relevant) documents from the stored collection.

---

## 🎯 Learning Objectives

After completing this lab, you will be able to:

1.  **Prepare and Preprocess Documents:** Get your text data ready for the embedding process.
2.  **Generate Embeddings:** Use **watsonx.ai's** embedding model to convert your documents into numerical vectors.
3.  **Store Embeddings:** Load and store these embeddings into two different vector databases: **Chroma DB** and **FAISS**.
4.  **Perform Similarity Searches:** Retrieve the most relevant documents from your vector database based on new inquiries.

---


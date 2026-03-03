BERT-Based Semantic Chatbot using Streamlit

This project is an AI-powered chatbot built using BERT (Bidirectional Encoder Representations from Transformers) and deployed with a Streamlit web interface. The chatbot leverages transformer-based embeddings and cosine similarity to understand user queries and provide context-aware responses from a predefined knowledge base.

🚀 Features

- 🤖 Transformer-based NLP using pretrained BERT model

- 🧠 Semantic similarity matching using cosine similarity

- ⚡ Cached model loading for improved performance

- 🎨 Custom background UI with Streamlit

- 💬 Interactive chatbot interface

🛠️ Tech Stack

- Python

- PyTorch

- Hugging Face Transformers

- Scikit-learn

- Streamlit

🧩 How It Works

- User inputs a query through the Streamlit interface.

- The input text is converted into embeddings using a pretrained BERT model.

- Cosine similarity is computed between the user query and predefined question embeddings.

- The most semantically similar question is selected.

- The corresponding response is returned if similarity exceeds a threshold.

🎯 Learning Outcomes

- Implemented transformer-based NLP models in real-world applications

- Applied sentence embeddings for semantic similarity tasks

- Built an interactive ML-powered web application using Streamlit

- Optimized inference performance using caching techniques

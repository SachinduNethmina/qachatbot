# YouTube QA Chatbot

This repository contains a simple **YouTube Question Answering (QA) Chatbot** that answers questions based on a given text file containing a list of sentences. The chatbot uses the **Sentence-Transformers** model (`all-MiniLM-L6-v2`) to provide context-based answers to user queries.

## Features
- **Single-chat conversation**: Ask a question, and the bot will return an answer based on the content in a provided text file.
- **Customizable**: You can update the text file with your own data and questions.
- **Pre-trained Model**: Uses the `all-MiniLM-L6-v2` model for efficient sentence embeddings and similarity comparison.
- **No history tracking**: This version supports only single question-answer interactions.

## Requirements

Before running the chatbot, ensure that you have the following installed:

- Python 3.6+
- `faiss-cpu` (for efficient similarity search)
- `sentence-transformers` (to encode questions and sentences)

### Install Dependencies

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/qa-chatbot.git
   cd qa-chatbot

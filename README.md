# Medical-Generative-ChatBot

### End-to-End Medical Chatbot with Generative AI

### Overview
### This project provides a complete implementation of a medical chatbot powered by Generative AI. It leverages state-of-the-art technologies including Python, LangChain, Flask, GPT, Pinecone, and AWS-CI to deliver a robust, scalable solution for medical applications.

### Getting Started

### 1. Clone the Repository

``` bash 
Project repo: https://github.com/
```

### 2. Set Up Your Python Environment

```bash
conda create -n medibot python=3.10 -y
conda activate medibot

```
### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
### In the root directory of the project, create a .env file. Insert your Pinecone and OpenAI credentials using the following format

```ini
PINECONE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### 5. Store Embeddings
```bash
python store_index.py
```

### 6. Launch the Application
```bash 
python app.py
```
### Now
```bash
Open up local host
```

### Technology Stack

- Python: Core programming language.

- LangChain: For language model orchestration.

- Flask: Lightweight web application framework.

- GPT: Generative Pre-trained Transformer for AI-driven responses.

- Pinecone: Vector database for managing embeddings.


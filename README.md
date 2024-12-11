# Question-answering-system-with-RAG-using-Gemini-Pro-and-Langchain Bangaldesh: An Overview

This system is designed to answer questions and provide insights about Bangladesh, covering topics such as history, geography, culture, and infrastructure. By utilizing advanced retrieval and language model techniques, the application delivers precise and concise answers based on the provided context.

# Features
Comprehensive Knowledge: Covers topics related to Bangladesh, including its history, geography, economy, and cultural heritage.
Intelligent Retrieval: Retrieves the most relevant information from a knowledge base for accurate responses.
Concise Answers: Provides clear and direct answers in three sentences or less.

# Requirements
Python 3.8+
Key Libraries: langchain, Chroma, GoogleGenerativeAIEmbeddings, dotenv

# Install dependencies:

pip install -r requirements.txt
# Set up your API keys:
Add your Google Generative AI API key to a **.env** file in the project directory:
GOOGLE_API_KEY=your_api_key

# Ask a Question: Input a question related to Bangladesh, such as:

"What is the history of the Liberation War of Bangladesh?"
"How many kilometers of railway does Bangladesh have?"
"What are the major rivers in Bangladesh?"
The system retrieves relevant context and generates concise answers.

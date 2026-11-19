# Hugging Face LLM Chatbot

## Overview

Hugging Face LLM Chatbot is a Python-based conversational AI application built using LangChain and Hugging Face.

The project integrates the Qwen3-8B Large Language Model (LLM) through Hugging Face Endpoint and uses LangChain to interact with the model.

It provides an interactive command-line interface where users can enter messages and receive AI-generated responses. The application also maintains conversation history during the session.

## Features

- Interactive command-line chatbot.
- Integration with Hugging Face language models.
- Uses Qwen3-8B for generating AI responses.
- Implements LangChain for LLM integration.
- Maintains conversation history during the session.
- Supports continuous conversations.
- Provides an exit command to terminate the chatbot.

## Technologies Used

- **Python** – Core programming language.
- **LangChain** – Framework for building applications with LLMs.
- **Hugging Face** – Provides access to pretrained language models.
- **Qwen3-8B** – Large Language Model used for generating responses.
- **Python-dotenv** – Loads environment variables from a `.env` file.

## Project Workflow

1. Import the required LangChain and Hugging Face libraries.
2. Load environment variables using Python-dotenv.
3. Configure the Hugging Face Endpoint with the Qwen3-8B model.
4. Initialize ChatHuggingFace to interact with the language model.
5. Create an empty list to maintain conversation history.
6. Accept user input through the command-line interface.
7. Pass the conversation history to the language model.
8. Generate and display the AI response.
9. Append the AI response to the conversation history.
10. Continue the conversation until the user enters `exit`.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/HemanthPotnuru2005/huggingface-llm-chatbot.git
```

### 2. Navigate to the Project Directory

```bash
cd huggingface-llm-chatbot
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 4. Install Required Libraries

```bash
pip install langchain-huggingface python-dotenv
```

### 5. Configure Hugging Face API Token

Create a `.env` file in the project directory.

Add your Hugging Face access token:

```env
HF_TOKEN=your_huggingface_access_token
```

Replace the placeholder with your actual Hugging Face token.

**Important:** Never upload your `.env` file or expose your API token on GitHub.

Add `.env` to your `.gitignore` file.

### 6. Run the Application

```bash
python main.py
```

## Example Interaction

```text
You : Hello!

AI : Hello! How can I help you today?

You : What is Machine Learning?

AI : Machine Learning is a branch of Artificial
     Intelligence that enables computers to learn
     from data and make predictions.

You : exit
```

*Example interaction for illustration purposes.*

## Key Learnings

Through this project, I learned:

- How to connect Hugging Face models with LangChain.
- How to configure Hugging Face Endpoints.
- How to work with Large Language Models (LLMs).
- How to use ChatHuggingFace and HuggingFaceEndpoint.
- How to maintain conversation history.
- How to load environment variables securely.
- How to build a basic conversational AI application.

## Future Improvements

- Implement structured conversation history using LangChain messages.
- Add streaming responses.
- Build a graphical user interface.
- Add support for different Hugging Face models.
- Implement conversation memory management.
- Add error handling and API connection management.
- Deploy the chatbot as a web application.

## Author

**Hemanth Potnuru**

- GitHub: [HemanthPotnuru2005](https://github.com/HemanthPotnuru2005)
- GitHub Profile: https://github.com/HemanthPotnuru2005

---

If you find this project useful, feel free to explore the repository!

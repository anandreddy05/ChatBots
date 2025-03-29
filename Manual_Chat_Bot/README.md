# ChatBot with Ollama and Streamlit
- This project is a simple chatbot built using Streamlit and LangChain Ollama to interact with LLMs (Large Language Models).
- It allows users to select a model, send messages, and receive responses, while maintaining chat history.

## Features
- Model Selection: Choose between different models like llama2:latest and deepseek-r1:7b.
- User Input: Accepts text input from the user.
- Response Generation: Uses LangChain's ChatOllama to generate responses.
- Chat History: Displays past messages for better interaction.
- Processing Time Display: Shows the response time for each query.

## Installation
Follow these steps to set up the chatbot:

1. Install Dependencies
Make sure you have Python installed (Python 3.9+ recommended).

Install the required Python packages:
```bash
pip install streamlit langchain_ollama
```
2. Install Ollama
You need to install Ollama to run models locally.

Windows: <https://ollama.com/ />

3 Download a Model
After installing Ollama, you need to download a model. Run:

```bash
ollama pull llama2:latest
```
```bash
ollama pull deepseek-r1:7b
```

4 Run the Streamlit App
Once everything is set up, navigate to the project folder and run:
```bash
streamlit run chatbot.py
```

## Usage
- Open the app in a browser (usually at http://localhost:8501).
- Select a model (llama2:latest or deepseek-r1:7b).
- Enter your message and press Send.
- View responses along with chat history.

# Simple ChatBot with Chat History

- This project is a Streamlit-powered AI chatbot that remembers previous user interactions. 
- It utilizes LangChain Ollama to process responses and supports multiple AI models.

## Features

- Multiple Model Support – Choose between mistral:latest, llama2:latest, and deepseek-r1:7b.
- Chat History – Maintains conversation context across interactions.
- Fast Processing – Displays response time for each interaction.
- Error Handling – Gracefully handles errors during model invocation.
- Simple & Clean UI – Built with Streamlit for an interactive experience.

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

Windows: https://ollama.com/ 

3 Download a Model
After installing Ollama, you need to download a model. Run:

```bash
ollama pull llama2:latest
```
```bash
ollama pull deepseek-r1:7b
```
```bash
ollama pull mistral:latest
```

4 Run the Streamlit App
Once everything is set up, navigate to the project folder and run:
```bash
streamlit run chatbot.py
```

## Usage
- Open the app in a browser (http://localhost:8501).
- Select a model from the dropdown (mistral:latest, llama2:latest, or deepseek-r1:7b).
- Type a message and click Send.
- View the chatbot’s response and chat history.

# ChatBot Using Local LLM

> In this project I am going to use RAG using Ollama, LangChain and Streamlit

## Business use case

This project showcases how chatbots answering candidate inquiries empower recruiters and HR. 

This is the dataset used: https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset/data 

# RAG (Retrieval Augmented Generation)

## What is RAG?

- It's a method to improve the answers of large language models (LLMs) by providing them with additional information from external sources.

- Imagine a huge library and an LLM as someone searching for information in those books.

- RAG is like having a helpful friend who not only points you to the relevant book but also adds extra details and explanations.

## Why is it useful?

- LLMs are trained on massive data, but they can still miss out on certain information or provide outdated answers.

- RAG allows them to access and integrate information from external sources, leading to more accurate and comprehensive responses.

- It's faster and more efficient than updating the LLM itself with new information every time.

# The players

- **Python 3.9.9.**

- **Ollama:** This lets you run fancy language models (LLMs) on your own computer, like having a super-smart assistant at your fingertips. 

- **LangChain:** This is the "recipe book" for building LLM-powered apps. It's like a framework for putting all the ingredients together and making something amazing. And guess what? We'll be using Python, a powerful and versatile language, to bring it all to life.

- **Streamlit:** Imagine building a sleek and user-friendly app interface without tons of coding. That's where Streamlit comes in! This handy library helps us create beautiful and easy-to-use interfaces for our web app, making it a joy to interact with.

# Ollama

I am going to use from this list at https://ollama.ai/library. I chose `neural-chat`, which it is a a fine-tuned model based on Mistral with good coverage of domain and language.

Before executing the chat bot app, we have to execute the Ubunta App an run on it ollama:

`ollama serve` and `ollama run neural-chat`


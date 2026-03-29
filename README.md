# LangChain & Google Gemini Integration 🤖

This repository explores the practical application of Google’s **Gemini 2.5 Flash** model within the **LangChain** ecosystem. It serves as a foundational resource for developers looking to move beyond simple API calls toward building structured, chain-based AI workflows.

## 🚀 Project Overview
The core objective is to demonstrate how to wrap Google's generative models in LangChain's modular architecture. By using prompt templates and chains, the project shows how to create reproducible and scalable AI interactions for tasks such as information retrieval and general-purpose assistance.

## 🔑 Key Features
* **Gemini LLM Orchestration**: Configuration and invocation of the `gemini-2.5-flash` model using `ChatGoogleGenerativeAI`.
* **Dynamic Prompt Engineering**: Creation of `PromptTemplates` to handle variable-based inputs for consistent model responses.
* **Chain Execution**: Implementation of the LangChain Expression Language (LCEL) to pipe templates directly into the model for streamlined execution.
* **External Context Awareness**: Foundational setup for integrating external data sources into the model's reasoning loop.

## 🛠️ Tech Stack
* **Language**: Python
* **LLM**: Google Gemini 2.5 Flash
* **Framework**: LangChain (langchain-google-genai)
* **Environment**: Jupyter Notebook / Google Colab

## ⚙️ Setup & Installation

### 1. Environment Configuration
It is recommended to use a dedicated environment to manage the specific API dependencies:

```bash
# Create and activate the environment
git clone https://github.com/Joe-Naz01/OpenAI.git
cd OpenAI

conda create -n gemini_langchain python=3.10 -y
conda activate gemini_langchain

# Install required packages
pip install -r requirements.txt
jupyter notebook